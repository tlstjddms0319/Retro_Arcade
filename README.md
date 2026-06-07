# 🕹️ Retro Arcade Community

레트로 미니게임 + 기록/랭킹/커뮤니티 플랫폼

## 기술 스택

| 구분 | 기술 |
|------|------|
| Frontend | Vanilla JS, HTML5 Canvas, CSS3 |
| Backend | Node.js, Express |
| Database | sql.js (WebAssembly SQLite) |
| 인증 | JWT, Google/Naver/Kakao OAuth 2.0 |
| 외부 API | Lichess Chess Puzzle API |

## 주요 기능

- 🎮 테트리스, 스네이크, 체스 퍼즐 미니게임
- 🏆 게임별 랭킹 및 내 기록 조회
- 💬 커뮤니티 게시판 (작성/수정/삭제/댓글)
- 🔐 소셜 로그인 (Google, Naver, Kakao)
- ♟️ Lichess 외부 API 연동 — 204개 퍼즐 풀 무한 제공

## 실행 방법

```bash
npm install
node server.js
# http://localhost:3000 접속
```

## 환경 변수 (.env)

```
GOOGLE_CLIENT_ID=...
NAVER_CLIENT_ID=...
KAKAO_CLIENT_ID=...
JWT_SECRET=...
PORT=3000
```
