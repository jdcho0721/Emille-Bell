# 에밀레: 천년의 울림
### Emille: Resonance of a Thousand Years

<p align="center">
  <img src="https://img.shields.io/badge/WCAG-2.1%20AA-4CAF50?style=flat-square" alt="WCAG 2.1 AA">
  <img src="https://img.shields.io/badge/PWA-Offline%20Ready-5A67D8?style=flat-square" alt="PWA">
  <img src="https://img.shields.io/badge/License-MIT-A07840?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/Humartology-Lab-1A362D?style=flat-square" alt="Humartology Lab">
</p>

<p align="center">
  <b>성덕대왕신종의 문양 미학과 맥놀이 현상을 소리와 리듬으로 치환한 다감각 인터랙티브 작품</b><br>
  <i>A multisensory interactive work translating the pattern aesthetics and beating phenomenon of the Silla Bell into sound and rhythm</i>
</p>

---

## 프로젝트 소개 / Overview

**에밀레: 천년의 울림**은 국보 성덕대왕신종(聖德大王神鐘, 일명 에밀레종)의 고유한 문양 미학과 맥놀이(beating) 현상을 소리와 리듬으로 치환하여 다감각적으로 재해석한 작품입니다.

비천상(飛天像), 용뉴(龍鈕) 등 신종의 대표 문양을 직접 만지는 촉각 패널과 연동하여, 천년의 침묵을 깨우고 장애의 장벽을 뛰어넘는 다감각 교감을 실현합니다.

*Emille: Resonance of a Thousand Years* translates the unique pattern aesthetics and beating phenomenon of Korea's National Treasure Silla Bell into sound and rhythm. Connected to tactile panels of the bell's iconic patterns — flying apsaras and dragon knobs — it awakens a thousand years of silence and transcends the barriers of disability.

> **"천년의 침묵을 깨우고 장애의 장벽을 뛰어넘는 다감각 교감."**

---

## 주요 기능 / Features

### 🔔 맥놀이 사운드 / Beating Phenomenon Sound
- 성덕대왕신종 고유의 맥놀이(beating) 파형 디지털 재현
- 종소리의 고유한 파형과 울림을 시각적·청각적 상호작용으로 변환
- 타격 지점과 세기에 따라 반응하는 동적 사운드스케이프

### 🎵 전통과 현대의 조화 / Traditional Meets Contemporary
- 전통 국악 선율과 현대적 앰비언트 사운드의 감각적 조화
- 비천상의 선율 → 청아한 가야금 음색
- 용뉴의 울림 → 웅장한 저음 드론

### 👆 촉각 패널 연동 / Tactile Panel Integration
| 문양 | 의미 | 사운드 특성 |
|------|------|------------|
| 비천상(飛天像) | 하늘을 나는 천인 | 높고 투명한 현악 선율 |
| 용뉴(龍鈕) | 종을 매다는 용 | 깊고 웅장한 저음 울림 |
| 연화문(蓮花紋) | 정화와 극락 | 맑고 잔잔한 수면 리듬 |
| 비천주악(飛天奏樂) | 악기를 연주하는 천인 | 전통 관악의 선율 |

### ♿ 접근성 / Accessibility
- **WCAG 2.1 AA** 준수
- **TalkBack / VoiceOver** 완벽 지원
- 시각 없이 천년 문화유산의 울림을 온몸으로 체감 가능

---

## 작품 배경 / Background

성덕대왕신종은 신라 경덕왕이 아버지 성덕왕을 기리기 위해 주조를 시작하여 771년(혜공왕 7년)에 완성된 높이 3.75m, 무게 18.9톤의 대형 범종입니다. 국보 제29호로 지정된 이 종은 에밀레종이라는 별칭으로도 알려져 있으며, 그 독특한 맥놀이 소리는 세계적으로 독보적인 음향 특성을 지닙니다.

The Divine Bell of King Seongdeok (Emille Bell), completed in 771 CE, is Korea's largest and most celebrated bronze bell, standing 3.75m tall and weighing 18.9 tons. Designated National Treasure No. 29, its unique beating phenomenon creates an acoustically unparalleled resonance recognized worldwide.

---

## 실행 방법 / Getting Started

```bash
git clone https://github.com/jdcho0721/Emille-Bell.git
cd Emille-Bell
npx serve .
# http://localhost:3000
```

**라이브 데모 / Live Demo:**  
🔗 [jdcho0721.github.io/Emille-Bell/](https://jdcho0721.github.io/Emille-Bell/)

---

## 기술 스택 / Tech Stack

| 분류 | 기술 |
|------|------|
| 프론트엔드 | Vanilla HTML / CSS / JavaScript |
| 오디오 | Web Audio API, OscillatorNode (맥놀이 구현) |
| 시각화 | Canvas API, SVG Animation |
| PWA | Service Worker, Web App Manifest |
| 접근성 | WAI-ARIA, WCAG 2.1 AA |

---

## Mobile Tactile Museum 전시 / Exhibition

이 작품은 **Mobile Tactile Museum (이동 촉각 뮤지엄)** 전시의 **Work 05 — Sound & Rhythm**입니다.

| # | 작품 | 링크 |
|---|------|------|
| 01 | 오우가와 세연정: 공간의 교향곡 | [Seyeon](https://github.com/jdcho0721/Seyeon) |
| 02 | 반가사유상: 사유의 목소리 | [Pensive-Bodhisattva](https://github.com/jdcho0721/Pensive-Bodhisattva) |
| 03 | 감각의 고고학 2076: 잃어버린 향의 연대기 | [Incense-Burner](https://github.com/jdcho0721/Incense-Burner) |
| 04 | 전북맹아학교를 위한 촉각 음성 졸업 앨범 | [Relay-of-memories](https://github.com/jdcho0721/Relay-of-memories) |
| 05 | **에밀레: 천년의 울림** | 현재 저장소 |

---

## 제작진 / Credits

| 역할 | 이름 | 소속 |
|------|------|------|
| Exhibition Creator & Multisensory Interaction Director | **조준동 (Cho Jundong)** | 성균관대학교 정보통신대학 명예교수 · Humartology Lab 설립자 |
| Virtual Archaeology & Tactile Production Director | **김호용** | (주)위프코 대표 |
| Accessibility Consultant & Barrier-Free Supervisor | **육근해** | 장애인문화복지연구소 대표 |

✉ jdcho@skku.edu · 🌐 [blog.naver.com/humartology](https://blog.naver.com/humartology)

---

## 라이선스 / License

[MIT License](./LICENSE) — © 2026 조준동 · Humartology Lab

> 성덕대왕신종 이미지는 국립경주박물관 소장품으로, 별도의 저작권 규정이 적용됩니다.  
> *The Divine Bell image is housed at the Gyeongju National Museum; separate copyright regulations apply.*

<p align="center"><i>Mobile Tactile Museum — 이동 촉각 뮤지엄 · 2026</i></p>
