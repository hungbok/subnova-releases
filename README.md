<p align="center"><img src="https://raw.githubusercontent.com/hungbok/subnova-releases/main/icon.png" width="96" alt="SubNova"></p>

<h1 align="center">SubNova</h1>

<p align="center">
  <b>한국어</b> · <a href="#english">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.zh-TW.md">繁體中文</a>
</p>

<p align="center"><a href="https://github.com/hungbok/subnova-releases/releases/latest"><b>⬇ 최신 버전 내려받기 / Download the latest version</b></a></p>

---

## 한국어

**SubNova**는 ASS 자막을 직관적으로 편집하는 데 초점을 맞춘 Windows용 모던 자막 편집기입니다.
영상 위에서 마우스로 위치·회전·클립·그리기를 편집하고, 실제 재생기와 똑같은 화면(libass)으로 결과를 확인할 수 있습니다.

### 주요 기능
- **실제와 똑같은 미리보기** — mpv 등 재생기가 쓰는 libass로 자막을 그립니다. 설치된 글꼴을 한글 이름으로도 찾습니다
- **영상 위 비주얼 편집** — 위치, 이동, 회전, 크기, 클립, 그리기(채우기 색 포함), 가이드 격자로 영상 속 평면에 맞추는 **평면 원근 도구**
- **빠른 태그 도구** — 글꼴, 색상·불투명도, 테두리·그림자·흐림, 회전·기울이기, 페이드, 정렬을 클릭 몇 번으로
- **자유로운 패널 배치** — 영상·자막 목록·자막 설정·자막 내용·타임라인·태그·시간 이동 패널을 원하는 자리에. 배치를 저장해 두고 불러오며, 창 크기·위치와 패널 크기를 다음 실행 때도 그대로
- **번역** — 번역 서비스·AI(DeepL, Google, Azure, Papago, OpenAI, Claude, Gemini, 키 없이 쓰는 무료 서비스)로 자동 번역하거나, 줄 단위로 복사해 원하는 번역기에 붙여 넣고 결과를 다시 붙여 넣는 방식으로 번역. 원문을 바꾸거나 원문 아래에 번역 줄로 추가
- **타임라인** — 오디오 파형 자동 표시, 블록 높이 조절, 드래그로 타이밍 편집, 실시간 시간 이동 패널
- **자막과 영상 자동 연결** — 같은 이름의 영상(`name.ko.ass` → `name.mkv`)이나 전에 함께 쓴 영상을 자동으로 불러옵니다
- **다양한 형식** — ASS/SSA, SRT, WebVTT, SAMI, TTML, SBV, MicroDVD, SCC, EBU STL, JSON/CSV 등 열기·저장·일괄 변환, Blu-ray/DVD 이미지 자막은 문자 인식(OCR)으로 가져오기
- **싱크 도구** — 시간 이동, 프레임 레이트 변환, 속도 변경, 두 지점 동기화, 다른 자막을 기준으로 동기화
- 다크/라이트 테마, 여러 창, 자동 업데이트, 파일 연결, 한국어·English·日本語·简体中文·繁體中文

### 설치
1. [Releases](https://github.com/hungbok/subnova-releases/releases/latest)에서 `SubNova-Setup-<버전>.exe`를 내려받아 실행합니다
2. 모든 사용자용으로 설치되므로 관리자 권한 확인(UAC)이 한 번 나타납니다
   - Windows SmartScreen 경고가 나오면 "추가 정보" → "실행"을 누르세요

### 업데이트
SubNova가 새 버전을 자동으로 확인하고 내려받습니다. "다시 시작하여 업데이트"를 누르거나 프로그램을 종료하면 설치됩니다. 도움말 → 업데이트 확인으로 직접 확인할 수도 있습니다.

---

## English

**SubNova** is a modern subtitle editor for Windows, built around intuitive ASS editing.
Edit position, rotation, clips and drawings with the mouse right on the video, and see the result exactly as players show it (libass).

### Highlights
- **True-to-life preview** — subtitles are rendered by libass, the renderer mpv and other players use, with your installed fonts
- **Visual editing on the video** — position, movement, rotation, scale, clips, drawings (with fill colour) and a **plane perspective tool** that fits text to a surface in the video with a guide grid
- **Quick tag tools** — font, colours and alpha, border/shadow/blur, rotation/shear, fade and alignment in a few clicks
- **Custom panel layout** — place the video, subtitle list, line settings, line text, timeline, tags and time-shift panels where you like; save and load layouts, and the window size, position and panel sizes are kept for the next launch
- **Translation** — translate automatically with translation services and AI (DeepL, Google, Azure, Papago, OpenAI, Claude, Gemini, and free services that need no key), or copy lines to any translator and paste the result back; replace the original or add the translation as new lines below it
- **Timeline** — automatic audio waveform, adjustable block height, drag to retime, live time-shift panel
- **Subtitle ↔ video pairing** — opening a subtitle also loads its video: one with the same name (`name.en.ass` → `name.mkv`) or the one you used with it before
- **Many formats** — open, save and batch-convert ASS/SSA, SRT, WebVTT, SAMI, TTML, SBV, MicroDVD, SCC, EBU STL, JSON/CSV and more; import Blu-ray/DVD image subtitles with OCR
- **Sync tools** — shift, frame-rate conversion, speed change, two-point sync, sync to another subtitle
- Dark/light themes, multiple windows, auto-update, file associations; Korean, English, Japanese, Simplified and Traditional Chinese

### Install
1. Download `SubNova-Setup-<version>.exe` from [Releases](https://github.com/hungbok/subnova-releases/releases/latest) and run it
2. SubNova installs for all users, so Windows asks for administrator approval (UAC) once
   - If Windows SmartScreen warns you, choose "More info" → "Run anyway"

### Updates
SubNova checks for and downloads new versions automatically. Click "Restart and update", or the update installs when you quit. You can also check via Help → Check for updates.

---

<p align="center">Developer: HungBok</p>
