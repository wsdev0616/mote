# mote - Lightweight Portable Notepad for Windows

**한국어** | [English](#english)

설치 없이 바로 쓰는 가벼운 Windows 메모장입니다.
`mote.exe` 파일 하나만 있으면 되고, 메모는 실행 파일과 같은 폴더에 저장됩니다.

## 다운로드

[**최신 버전 받기 (Releases)**](../../releases/latest) → `mote.exe`를 내려받아 원하는 폴더에 두고 실행하세요.

- 지원 환경: Windows 10 / 11 (64비트)
- WebView2 런타임이 필요합니다. Windows 11과 최신 Windows 10에는 기본으로 설치되어 있습니다.

## 주요 기능

- **포터블** — 설치 과정이 없습니다. 실행하면 같은 폴더에 `mote.db`(메모·설정)와 `backup\` 폴더가 생깁니다. 폴더째 옮기면 메모도 함께 옮겨집니다.
- **자동 저장** — 입력을 멈추면 바로 저장되고, 쉬지 않고 입력해도 5초마다 저장됩니다.
- **자동 백업** — 실행한 날마다 하루 한 번 백업하고, 최근 3일치를 보관합니다.
- **빠른 검색** — `Ctrl+K`로 모든 메모의 제목과 본문을 검색합니다.
- **메모 안 찾기·바꾸기** — 대소문자 구분, 단어 단위, 정규식을 지원합니다.
- **편리한 목록** — 메모를 고정하거나 날짜별로 묶어 볼 수 있고, 삭제해도 바로 실행 취소할 수 있습니다.
- **가져오기·내보내기** — `.txt`, `.md` 파일을 가져오고 내보냅니다. 예전 한글 메모장 파일(CP949)도 읽습니다.
- **나만의 설정** — 라이트/다크 테마, 에디터 글꼴과 크기, 줄 번호, 자동 줄바꿈, 항상 위에 표시, 단축키를 바꿀 수 있습니다.
- **자동 업데이트** — 새 버전이 나오면 알려 주고, 클릭 한 번으로 업데이트합니다. 업데이트 파일은 서명으로 검증합니다.

## 기본 단축키

| 동작 | 단축키 |
|---|---|
| 새 메모 | `Ctrl+N` |
| 전체 메모 검색 | `Ctrl+K` |
| 메모 안 찾기 / 바꾸기 | `Ctrl+F` / `Ctrl+H` |
| 즉시 저장 | `Ctrl+S` |
| 현재 메모 삭제 | `Ctrl+Shift+Delete` |
| 사이드바 접기 | `Ctrl+B` |
| 자동 줄바꿈 켜기/끄기 | `Alt+Z` |
| 글자 크게 / 작게 / 기본 | `Ctrl++` / `Ctrl+-` / `Ctrl+0` |
| 가져오기 / 현재 메모 내보내기 | `Ctrl+O` / `Ctrl+Shift+S` |
| 설정 | `Ctrl+,` |

단축키는 설정 → 단축키 탭에서 바꿀 수 있습니다.

## 데이터와 백업

- 메모와 설정은 모두 `mote.exe` 옆의 `mote.db` 파일 하나에 들어 있습니다.
- 백업 파일은 `backup\mote-YYYY-MM-DD.db` 형식으로 저장됩니다. 복원하려면 mote를 종료한 뒤, 백업 파일을 `mote.db`라는 이름으로 바꿔 덮어쓰세요. 덮어쓰기 전에 현재 `mote.db`를 따로 복사해 두는 것을 권장합니다.
- `Program Files`처럼 쓰기 권한이 없는 폴더에서 실행하면 메모가 `%APPDATA%`에 저장됩니다. 이때 자동 업데이트는 직접 내려받기 안내로 대신합니다.

## 라이선스 고지

- 이 저장소에는 배포용 실행 파일만 올라옵니다.
- UI 글꼴로 [Pretendard](https://github.com/orioncactus/pretendard)(SIL Open Font License 1.1)를 사용합니다.

---

<a id="english"></a>

# mote

[한국어](#mote) | **English**

A lightweight, no-install notepad for Windows.
All you need is a single `mote.exe` file. Your notes are saved in the same folder as the executable.

## Download

[**Get the latest version (Releases)**](../../releases/latest) → download `mote.exe`, put it in any folder, and run it.

- Supported: Windows 10 / 11 (64-bit)
- Requires the WebView2 Runtime, which comes preinstalled on Windows 11 and recent versions of Windows 10.

## Features

- **Portable** — No installation. On first run, mote creates `mote.db` (notes and settings) and a `backup\` folder next to the executable. Move the folder and your notes move with it.
- **Autosave** — Saves as soon as you pause typing, and at least every 5 seconds while you keep typing.
- **Automatic backups** — Backs up once a day on each day you use it, keeping the last 3 days.
- **Quick search** — Press `Ctrl+K` to search the titles and contents of all notes.
- **Find and replace in a note** — Supports match case, whole word, and regular expressions.
- **Handy note list** — Pin notes, browse them grouped by date, and undo a delete right away.
- **Import and export** — Import and export `.txt` and `.md` files, including legacy Korean (CP949) text files.
- **Your preferences** — Light/dark theme, editor font and size, line numbers, word wrap, always on top, and custom shortcuts.
- **Automatic updates** — mote tells you when a new version is out and updates with one click. Update files are verified with a signature.

## Default shortcuts

| Action | Shortcut |
|---|---|
| New note | `Ctrl+N` |
| Search all notes | `Ctrl+K` |
| Find / replace in note | `Ctrl+F` / `Ctrl+H` |
| Save now | `Ctrl+S` |
| Delete current note | `Ctrl+Shift+Delete` |
| Toggle sidebar | `Ctrl+B` |
| Toggle word wrap | `Alt+Z` |
| Zoom in / out / reset | `Ctrl++` / `Ctrl+-` / `Ctrl+0` |
| Import / export current note | `Ctrl+O` / `Ctrl+Shift+S` |
| Settings | `Ctrl+,` |

You can change shortcuts under Settings → Shortcuts.

## Data and backups

- All notes and settings live in a single file, `mote.db`, next to `mote.exe`.
- Backups are saved as `backup\mote-YYYY-MM-DD.db`. To restore one, quit mote, then rename the backup to `mote.db` and replace the existing file. We recommend copying your current `mote.db` somewhere safe first.
- If you run mote from a folder without write access (such as `Program Files`), notes are saved to `%APPDATA%` instead. In that case, automatic updates fall back to a link for downloading the new version manually.

## Licenses

- This repository only hosts release builds.
- The UI font is [Pretendard](https://github.com/orioncactus/pretendard) (SIL Open Font License 1.1).
