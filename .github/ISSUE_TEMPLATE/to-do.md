---
name: To Do
about: 구현에 따라 체크박스를 하나씩 체크해가면서, 프로젝트의 필수 혹은 권장할 만한 진행 상황을 확인
title: To-Do-List 작성하기
labels: ''
assignees: ''

---

우선 순위: 필수 > 권장 > 도전 순으로

# 🌝 Bare Minimum(필수)

## 1. 시스템 아키텍처

- [ ]  JWT를 이용한 로그인 구현 | 필수 | ★

## 2. UI/UX

- [x]  페이지 리스트업
    - [ ]  랜딩페이지
    - [ ]  롤링페이퍼 출력 화면
    - [ ]  롤링페이퍼 작성 화면
    - [ ]  회원가입
    - [ ]  마이페이지 → 유저/관리자
- [ ]  와이어프레임 작성: Ziteboard 사용
- [ ]  라이브러리를 사용하지 않고 React 컴포넌트 직접 작성 | 필수 | ★
- [ ]  3rd-party API 호출 | 권장 | ★
- [ ]  라이브러리를 사용하지 않고 React 컴포넌트 직접 작성 | 권장 | ★★★
- [ ]  S3로 파일 업로드 | 권장 | ★★★

## 3. 스키마 및 API

- [ ]  N:M (다대다) 관계 설정 | 필수 | ★
- [ ]  ERD (DB Diagram) 작성 | 필수 | ★
    - [ ]  필요한 테이블 정의
    - [ ]  각 테이블의 컬럼
    - [ ]  테이블 간 관계 설정
- [ ]  API 작성: Gitbook API 사용 | 필수 | ★★
- [ ]  ORM 사용 (sequelize) | 권장 | ★

## 4. DevOps

- [ ]  \[코드\] precommit 단계에서 Lint:semistandard 적용 | 필수 | ★
- [x]  \[코드\] 버전 규칙 합의 | 필수 | ★
- [x]  \[릴리즈\] 깃허브 커밋메세지 규칙 합의 | 필수 | ★
- [x]  \[릴리즈\] PR 형식 합의 | 권장 | ★
- [ ]  \[배포\] 배포 자동화 설정 | 권장 | ★
- [ ]  \[배포\] 도메인 구매 및 HTTPS 배포 | 권장 | ★★★

# 🌗 Advanced (도전) 항목

도전 항목은 유어클래스의 To do 리스트를 참고하세요.
- [ ]  모바일 환경 대응 및 반응형 웹 | 권장 | ★★

- [ ]  페이지네이션 구현 | 권장 | ★★★
- [ ]  회원 가입시 인증 메일 발송 | 권장 | ★★★
- [ ]  OAuth 2.0을 이용한 카카오톡 소셜 로그인 | 권장 | ★

- [ ]  \[테스트\] 백엔드 테스트 코드 작성 | 권장 | ★★★
- [ ]  \[테스트\] w3c validator 통과 | 권장 | ★★★

# 🌚 Nightmare (신중) 항목
