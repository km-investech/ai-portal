# AI작업

자주 쓰는 앱·도구 바로가기 포털. `index.html` 파일 하나로 완결됩니다 (외부 의존성 없음).

## 들어있는 링크

**내 앱 (Vercel)**

| 앱 | 주소 |
| --- | --- |
| 전신질환 정보 분석 | https://dental-safety-guideline.vercel.app |
| 정시컨설팅 | https://univconsulting.vercel.app |
| 펜 담체화 풍경스케치 교재 | https://watercolor-sketch-peyzzz.vercel.app |
| Surgical Risk Tool | https://surgical-risk-tool.vercel.app |
| 치과 개원 시뮬레이터 | https://mediscope-coral.vercel.app |
| 병원 매출분석 | https://hospital-revenue.vercel.app |
| 은퇴 계산기 | https://retirement-calc-one.vercel.app |

**AI 도구** — ChatGPT, Claude, Gemini, GitHub(@km-investech), Vercel

## 올리는 방법 (10초)

### 1) GitHub Pages
1. https://github.com/new?name=ai-portal 에서 저장소 `ai-portal` 을 Public 으로 만듭니다.
2. 아래 두 줄을 실행하면 파일이 올라갑니다.

```bash
git clone https://github.com/<사용자>/ai-portal.git && cd ai-portal
cp /경로/index.html . && git add . && git commit -m "Add AI작업 portal" && git push
```

3. 저장소 Settings → Pages → Branch: `main`, 폴더: `/ (root)` → Save
4. 1~2분 뒤 https://km-investech.github.io/ai-portal/ 에서 열립니다.

### 2) Vercel
`index.html` 을 담은 폴더를 Vercel 대시보드에 그대로 드래그&드롭하면 끝입니다. 빌드 설정은 필요 없습니다(정적 파일).

### 3) 휴대폰 홈 화면에 추가
배포된 주소를 휴대폰 브라우저로 연 뒤,
- Android Chrome: 우측 상단 ⋮ → **홈 화면에 추가**
- iPhone Safari: 공유 → **홈 화면에 추가**

앱 아이콘처럼 실행되고, 각 카드는 새 탭(새 창)으로 열립니다.
