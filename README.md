# Japanese Shadowing 홈페이지 (영어 채널) — 자동 업데이트

영어 채널 [Japanese Shadowing](https://www.youtube.com/@japaneseshadowing)의 영상 목록 홈페이지입니다.
한국어 채널 사이트(shadowing-home)와 같은 구조이며, 매일 아침 6시(한국시간)에 자동 갱신됩니다.

## 설정 (기존 사이트와 동일)

1. 새 저장소 `japanese-shadowing-home` (Public)
2. 파일 전체 업로드 (`.github/workflows/update.yml` 포함)
3. Settings → Secrets and variables → Actions → `YT_API_KEY` 등록 (기존과 같은 키 재사용 가능)
4. Settings → Pages → main / (root) → Save
5. Actions → Run workflow

완성 주소: `https://shadowingjapan.github.io/japanese-shadowing-home/`
