# 카카오 테크 캠퍼스 - 프론트엔드 카카오 선물하기 편

## Step 1 📝요구사항
### 상품 상세 페이지와 상품 결제하기 페이지 form 로직 구현
- [ ] 상품 결제 페이지의 UI 구현하기
  - [ ] Chakra UI를 사용하여 구현
- [ ] 상세 페이지에서 첨부된 oas.yaml 파일의 `/api/v1/products/{productId}/detail`, `/api/v1/products/{productId}/options`를 참고하여 API를 구현한다.
- [ ] 없는 상품의 경우 메인 페이지로 연결되도록 한다.
- [ ] '나에게 선물하기' 버튼 클릭 시 로그인이 되어있지 않다면 로그인 페이지로 이동한다.
- [ ] React Hook Form 등의 라이브러리를 사용하지 않으며 React의 form, ref, state만 사용하여 구현한다.

## Step 1 📝구현할 기능
### 1. 상품 상세 페이지
- [ ] 상품 정보를 보여주는 UI 구현
  - [ ] 상품 이미지
  - [ ] 상품 이름
  - [ ] 상품 가격
  - [ ] 코드로 선물 가능 문구
- [ ] 상품 옵션을 선택할 수 있는 UI 구현
  - [ ] 수량 선택
- [ ] '나에게 선물하기' 버튼 구현
  - [ ] 로그인이 되어있다면 결제 페이지로 이동
  - [ ] 클릭 시 로그인 여부를 확인하고 로그인 페이지로 이동하는 로직 구현
    - [ ] alert로 로그인 이동 여부 확인
  - [ ] 없는 상품일 경우 메인 페이지로 리다이렉트하는 로직 구현

### 2. 상품 결제 페이지
- [ ] 메세지 입력란 구현
  - [ ] 내용을 입력하지 않으면 alert문 출력 
- [ ] 결제 정보 입력 폼 UI 구현
  - [ ] 현금영수증 신청 체크박스
  - [ ] 소득공제 유형 선택 드롭다운
  - [ ] 소득공제 전화 번호 입력 필드
- [ ] 최종 결제금액 표시
- [ ] 선물내역 섹션 구현
  - [ ] 상품 이미지
  - [ ] 상품 이름 및 수량
- [ ] 결제 버튼 구현
  - [ ] 클릭 시 결제 정보를 확인하고 결제를 진행하는 로직 구현

### 3. API
- [ ] 상품 상세 정보 API 호출
  - [ ] `/api/v1/products/{productId}/detail`
- [ ] 상품 옵션 정보 API 호출
  - [ ] `/api/v1/products/{productId}/options`

