# JobTrack — Landing Page

JobTrack 앱(https://job-kappa-coral.vercel.app)의 마케팅 랜딩 페이지.

## 구조

- 단일 정적 HTML (`index.html`)
- Tailwind CSS via CDN
- Pretendard 폰트 (jsdelivr CDN)
- Vercel 정적 배포

## 로컬 미리보기

```bash
# 그냥 브라우저로 index.html 열기
open index.html

# 또는 정적 서버
npx serve .
```

## 배포

Vercel에 GitHub 레포 import → 자동 배포. 빌드 명령 불필요.

## 콘텐츠 변경

`index.html`만 수정하고 push하면 Vercel이 자동 재배포.
