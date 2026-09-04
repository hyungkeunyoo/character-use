HY ERICA 캐릭터 사용 승인센터 v2.2.0

구성
- index.html : GitHub Pages 공개 신청 화면
- assets/hanyang-card.webp : 하냥이 카드 이미지
- assets/hibibi-card.webp : 하이비비 카드 이미지
- assets/hanyang_manual.pdf : 하냥이 매뉴얼
- assets/hibibi_manual.pdf : 하이비비 매뉴얼

공개 화면 기능
- 사용 가능 여부 자동 판정
- Cloudflare Turnstile 검증
- 신청번호 생성 및 Google Apps Script 전송
- Google Sheets 신청 이력 기록
- PNG/JPG/PDF 첨부 전송
- 담당자 접수 메일 발송
- 첨부 시안 비공개 Google Drive 보관

v2.2.0 승인 기능
- 접수 메일 승인 / 보완요청 / 사용불가 검토 버튼
- 별도 관리자 Apps Script에서 목록·상세·상태 처리
- HMAC 서명·만료·1회 사용 검증
- 신청자 결과 메일 및 별도 승인이력 기록

배포
1. GitHub Pages는 main / root를 사용한다.
2. 공개 신청 Apps Script와 관리자 Apps Script는 보안상 별도 프로젝트로 배포한다.
3. Apps Script 설정 및 배포 순서는 별도 배포 가이드를 따른다.
