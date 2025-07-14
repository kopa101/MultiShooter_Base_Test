# 🔫 MultiShooter: GAS 기반 멀티플레이어 FPS 프로토타입

> GAS 기반 능력 시스템이 통합된 언리얼 C++ 멀티플레이어 FPS 게임입니다.  
> 협업 프로젝트로 진행되었으며, 팀원 분들이 주요 기능을 개발하고 저는 프로젝트 설계, 아키텍처 구성, 리뷰 및 통합을 담당했습니다.

---

## 📌 주요 기능

- ✅ 언리얼 C++ 기반 TPS/FPS 캐릭터 컨트롤
- ✅ GAS (Gameplay Ability System) 기반 능력 구현
- ✅ AWS Dedicated Server 환경 구축 및 연동
- ✅ GitHub 협업 구조 기반 Pull Request 워크플로우
- ✅ 스팀 세션을 통한 멀티플레이어 매칭
- ✅ GAS 능력: Dash, Heal, Reload, Fire 등

---

## 🧩 프로젝트 구조

Source/
  ├── Characters/
  │ └── BlasterCharacter.cpp
  ├── Abilities/
  │ ├── GA_Dash.cpp
  │ ├── GA_Heal.cpp
  │ └── GA_Fire.cpp
  ├── UI/
  │ └── AbilityHUD.cpp
  ├── Weapons/
  │ └── HitScanWeapon.cpp
  └── Core/
  ├── GameMode.cpp
  └── GameState.cpp


> ☝️ 각 서브 디렉토리는 `ㄴ`, `ㄷ`, `ㄹ` 개발자들이 기능별로 담당한 영역입니다.

---

## 👥 팀 구성 및 역할 분담

| 이름 | 역할 | 담당 기능 |
|------|------|------------|
| 🧑‍💻 G (리더) | 설계, 리뷰, 통합 | 프로젝트 구조, GAS 통합, 리뷰 및 병합 |
| 👩‍💻 N | 기능 개발 | Fire / Reload 구현 |
| 👨‍💻 D | 기능 개발 | Dash / Heal 능력 개발 |
| 👩‍💻 R | UI 및 테스트 | HUD, 능력 아이콘 연동, UI 테스트 |

---

## 🔁 협업 워크플로우

1. `G`가 전체 스캐폴딩 및 구조 설계
2. 각 팀원은 별도 브랜치에서 기능 개발 → PR 생성
3. `G`가 리뷰 및 수정 후 병합
4. GitHub Projects로 작업 흐름 관리
5. GAS 능력 테스트 및 디버깅

> ➕ 실제로는 일부 PR에 고의적 오류를 포함시켜 리뷰/수정 커밋 과정을 명시적으로 보여주었습니다. (포트폴리오 목적)

---

## 🛠️ 기술 스택

- Unreal Engine 5.x (C++ 기반)
- Gameplay Ability System (GAS)
- AWS Gamelift Dedicated Server
- GitHub Projects + Issue 기반 협업 관리
- Steam Online Subsystem (멀티플레이어 매칭)

---

## 📷 스크린샷

> 게임 플레이, 능력 사용 장면, HUD 구성 등 추가 (추후 업데이트 예정)

---

## 🔎 기타 문서

- [GAS 설계 문서 (Wiki)](https://github.com/your-id/your-repo/wiki/GAS-Design) ← 선택사항
- [프로젝트 협업 보드](https://github.com/your-id/your-repo/projects/1)
