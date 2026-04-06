# 포트폴리오 웹사이트

## 배포 방법

### GitHub Pages
1. 이 저장소의 Settings > Pages로 이동
2. Source에서 "Deploy from a branch" 선택
3. Branch를 main으로 설정하고 Save
4. https://leceau-droid.github.io/vibe-portfolio/ 에서 접속

### 다른 호스팅 서비스
- Netlify: index.html 파일 드래그앤드롭 배포
- Vercel: GitHub 연동으로 자동 배포
- Firebase Hosting: 정적 사이트 호스팅

## 로컬 실행
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .

# 브라우저에서 http://localhost:8000 접속
```
