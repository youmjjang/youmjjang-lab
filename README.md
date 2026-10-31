# youmjjang.lab

김유미의 **데이터·자동화·개발 포트폴리오** 웹사이트입니다. 기존 보안 중심 포트폴리오를 덮어쓰지 않고, 다양한 개발 직무에 맞춰 새로 구성한 독립 사이트입니다.

## 특징

- 응답형 정적 HTML/CSS/JavaScript: 빌드·별도 패키지 설치 불필요
- 프로젝트 분야 필터(All / Data & Automation / AI & Security / Web & Product)
- 실제 프로젝트 화면과 근거 있는 설명(HTTP Status Analyzer, GIGANG, Mini SOC, 쉬엄쉬엄, 오늘의짐)
- 키보드 탐색, 모바일 메뉴, 모션 감소 설정 지원
- 실제 팀 역할과 모의실험 지표의 범위를 구분

## 실행

`index.html`을 브라우저에서 열거나 프로젝트 폴더에서 아래 명령어를 실행하세요.

```bash
python -m http.server 8000
```

브라우저에서 `http://localhost:8000`으로 접속합니다.

## 배포

**Vercel**: 저장소를 Import한 뒤 Framework Preset을 `Other`, Build Command를 비워 두고 Output Directory를 `.`로 설정하면 됩니다. (정적 파일)

**GitHub Pages**: Repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/(root)`를 선택하면 됩니다. 배포 후 주소는 `https://youmjjang.github.io/youmjjang-lab/`입니다.

## 유지·수정

- 개인정보·문구·프로젝트 링크: `index.html`
- 색상·타이포그래피·모바일 화면: `styles.css`
- 모바일 메뉴와 프로젝트 필터: `script.js`
- 이미지는 기존 공개 GitHub 저장소의 실제 프로젝트 화면을 참조하므로, 이미지 저장소의 이름이나 경로가 변경되면 링크를 수정해야 합니다.
- 프로젝트 내용은 지원 직무에 따라 순서/강조점을 조절할 수 있습니다.

## 안내

- GIGANG은 팀 프로젝트입니다. 본인의 담당 범위는 수집·DB 연동·판단 흐름 보완·단말 대응 연결로 한정해 소개했습니다.
- HTTP Status Pattern Analyzer의 F1은 모의 실험 결과이며 실제 운영 공격 탐지 성능을 뜻하지 않습니다.
- Mini SOC의 잠금·차단 대응은 포트폴리오용 시뮬레이션입니다.
- 오늘의짐은 공공데이터 커버리지에 따른 진행 범위를 명시했습니다.
- 로그인, 백엔드, 사용자 데이터 수집·분석 스크립트는 없습니다.