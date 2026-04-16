# 💰 구걸 마스터: 프리미엄 에디션 (Begging Master: Premium Edition)

![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5 Canvas](https://img.shields.io/badge/HTML5_Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Local Storage](https://img.shields.io/badge/LocalStorage-007396?style=for-the-badge&logo=google-chrome&logoColor=white)

> **"단순한 구걸은 잊어라. 이제는 전략이다."** > 클릭에서 시작해 도시를 지배하는 자산가로 거듭나는 풀 구조 클릭커 방치형 RPG입니다.

---

## 업데이트 내용
## 2026.04.16 v2.1
1. 상점기능이 추가 됐습니다.
* 터치 물약(5x, 10x, 100x) 추가
* 자동 물약(5x, 10x, 100x) 추가
* 자동 터치 추가


2. 스킬이 추가 됐습니다.
* 클릭 파워
* 자동 속도
* 크리티컬 확률
* 크리티컬 데미지
* 골드 보너스
* 자산 효율


3. 상점기능이 추가 됐습니다. (모든 유물은 중첩됩니다.)
* 황금 왕관: 모든 골드 획득 50%
* x 크리티컬 검: 크리티컬 확률 20%
* 신속의 장화: 자동 수익 +30%
* 파워 링: 클릭 파워 +30%
* 행운의 동전: 다이아 드랍률 5%
* 마법서: 스킬 효과 15%
* 환생의 보석: 환생 보너스 25%
* 시간의 시계: 이벤트 효과 50%
* 행운의 고양이: 골드 획득 20%
* 동 메달: 클릭 파워 10%
* 은 메달: 자동 수익 10%
* 금 메달: 모든 능력 15%
* 고대 두루마리: 모든 능력 30%
* 불사조 깃털: 환생 보너스 20%
* 드래곤 비늘: 크리티컬 확률 15%

---

## 🎮 게임 루프 (Core Loop)

1. **클릭(Beg)**: 화면을 터치하여 기초 자산을 확보합니다.
2. **강화(Upgrade)**: 클릭 효율과 자동 수익을 높입니다.
3. **스킬(Skill)**: 영구적인 능력치를 높입니다.
4. **투자(Invest)**: 부동산, 미술품, 기업 등 자산을 수집하여 영구 버프를 획득합니다.
5. **상점(Shop)**: 자동 터치 기능, 터치 자동 배수 물약을 구입해 효과 적인 플레이가 가능합니다.
6. **유물(Relics)**: 영구적인 능력치를 높입니다.
7. **환생(Prestige)**: 성장이 정체될 때, 모든 것을 내려놓고 더 강력한 배율로 다시 시작합니다.

---

## ✨ 주요 기능

### 🖱️ 1. 하이퍼 클릭 시스템
* **크리티컬**: 최대 95% 확률의 크리티컬 시스템으로 폭발적인 수익 창출.
* **피드백**: Canvas 기반의 화려한 파티클 효과와 몰입감을 더하는 사운드 피드백.

### 📈 2. 심화된 강화 & 스킬 트리
* **다중 구매**: x10, x100 단위 구매로 빠른 성장 지원.
* **전략적 스킬**: 클릭, 자동 속도, 크리티컬, 자산 효율 중 원하는 경로 선택 가능.

### 🏢 3. 자산 시스템 (Asset Management)
단순한 숫자가 아닌, 테마별 자산 수집을 통한 영구적 능력치 상승.
* **부동산**: 클릭 수익 강화
* **미술품**: 크리티컬 데미지 효율 극대화
* **기업**: 자동 수익(Idle) 강화
* **도시**: 전체 수익 배율 증가

### ♻️ 4. 환생 & 랜덤 이벤트
* **Prestige 시스템**: 일정 골드 달성 후 환생 시 영구 멀티플라이어 제공.
* **돌발 이벤트**: 골드 2배 버프부터 긴장감을 주는 디버프 이벤트까지 발생.

### 📱 5. 모바일 최적화 및 UX
* **하이브리드 스크롤**: 가로(탭 전환)와 세로(컨텐츠) 스크롤 분리로 쾌적한 조작감.
* **iOS 대응**: 관성 스크롤 및 터치 인터랙션 최적화.

---

## 🛠 기술 스택 (Tech Stack)

* **Engine**: `HTML5 Canvas` (고성능 렌더링)
* **Logic**: `Vanilla JavaScript` (프레임워크 없는 순수 로직)
* **Audio**: `Web Audio API` (실시간 사운드 처리)
* **Persistence**: `LocalStorage` (5초 주기 자동 저장 및 데이터 유지)

---

## 📂 프로젝트 구조

```text
/project
 ├── index.html      # 핵심 게임 로직, 렌더링, UI가 통합된 Canvas 코드
 └── README.md       # 프로젝트 가이드
```

## 🚀 시작하기
별도의 빌드 과정이나 서버 설정이 필요하지 않습니다.

저장소 클론

Bash
```text
git clone [https://github.com/wunghuihwang/Begging-Remaster.git](https://github.com/wunghuihwang/Begging-Remaster.git)
cd Begging-Remaster
실행
```

index.html 파일을 브라우저로 더블클릭하여 실행하세요.

구걸 마스터: 프리미엄 에디션으로 부의 정점에 도전해보세요!
