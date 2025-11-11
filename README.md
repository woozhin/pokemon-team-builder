# ![메인 배너](./mainbanner.png)

# 🧢 Poketchoice  
### 포켓몬 배틀 초보자들을 위한 가이드라인 사이트

---

## 🎯 프로젝트 개요
**Poketchoice**는 포켓몬 배틀 입문자들이 손쉽게 팀을 구성하고,  
상성 및 기술 배치를 효율적으로 이해할 수 있도록 돕는 웹사이트입니다.  
배틀 초보자들이 **팀 빌딩과 전략 구성을 한눈에 파악**할 수 있도록 제작되었습니다.

---

## ⚙️ 주요 기능
- 🧩 **팀 만들기** — 사용자가 원하는 포켓몬으로 직접 팀 구성  
- 🧠 **추천 팀 조합** — AI 기반 혹은 데이터 기반으로 시너지 높은 팀 추천  
- 🔥 **상성표** — 타입별 상성표 및 피해 배율 정보 제공  
- ⚔️ **포켓몬별 추천 기술 배치도** — 각 포켓몬의 추천 기술 셋 시각화  
- 🎒 **지닌 아이템 추천** — 포켓몬별로 효과적인 아이템 자동 제안  
- 📈 **전략 분석 도구 (추가 예정)** — 팀 구성 효율 및 약점 분석

---

## 📷 미리보기
![미리보기](./mainreadme.png)

---

## 🛠️ 기술 스택 및 API

### 기술 스택
- **React 18** (CDN) - `team-builder.html`에서 동적 UI 구성 및 상태 관리
- **Babel Standalone** (CDN) - JSX 문법 변환
- **HTML5 / CSS3 / JavaScript (ES6+)** - 모든 페이지의 기본 구조 및 스타일링
- **CSS Grid & Flexbox** - 반응형 레이아웃 구성
- **JSX** - React 컴포넌트 작성 (`team-builder.html`)

### 사용 API
- **PokeAPI** - 포켓몬 및 아이템 이미지 제공 (모든 페이지)
- **Google Fonts** - 한글 폰트 (Noto Sans KR) 제공 (모든 페이지)
- **Fetch API** - 로컬 JSON 파일 비동기 로드 (`team-builder.html`, `team-recommendations.html`)
- **LocalStorage API** - 팀 저장/불러오기 및 페이지 간 데이터 전달 (`team-builder.html`, `team-recommendations.html`)

### 데이터 파일 (`data/` 폴더)
- `pokemoem_pokedex.json` - 포켓몬 기본 정보
- `pokemoem_pokemon_ranking_sc.json` - 포켓몬 인기 랭킹
- `pokemoem_typechart.json` - 타입 상성표
- `pokemoem_pokemon_details_sc.json` - 포켓몬 상세 정보 (추천 기술/아이템)
- `pokemoem_moves.json` - 기술 정보
- `pokemoem_items.json` - 지닌 도구 정보
- `pokemoem_abilities.json` - 특성 정보

---

## 📄 라이선스
이 프로젝트는 MIT 라이선스로 배포될 예정입니다.  
자유롭게 수정, 배포 가능하되 출처 명시를 권장합니다.

---

👑 **Poketchoice — 포켓몬 배틀 입문자들의 첫걸음을 함께합니다!**
