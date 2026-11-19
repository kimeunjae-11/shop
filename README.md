# REWORN — Vintage Archive

빈티지 의류 쇼핑몰 (수업 과제용 데모)

- 사이트: https://kimeunjae-11.github.io/hswb-week12/
- `index.html` 한 파일에 HTML · CSS · JS 포함, 이미지는 `img/` 폴더 (상대 경로)

## 기능
- 회원가입 / 로그인 (가입 시 3,000P 지급)
- 등급별 포인트 적립: BASIC 1% · SILVER 3% · GOLD 5% · VIP 7% (누적 구매 금액 기준 자동 승급)
- 장바구니, 결제(신용카드 / 무통장입금 / 간편결제 시뮬레이션), 포인트 사용
- 1점 한정 상품: 결제 후 SOLD OUT 처리
- 관리자 상품 등록 (사진 업로드 포함) — 아이디 `admin` / 비밀번호 `admin1234`
- 메인 슬라이드 4장 자동 전환, 카테고리 · 검색 · 정렬

회원 · 주문 데이터는 브라우저 localStorage에만 저장되며 실제 결제는 이루어지지 않습니다.
