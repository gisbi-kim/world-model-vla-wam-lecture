# World Model, VLA, WAM Lecture

Korean lecture note on the current structure of world models, Vision-Language-Action models, World Action Models, and embodied robot intelligence.

## Hosted Pages

- Main site: https://gisbi-kim.github.io/world-model-vla-wam-lecture/
- Lecture note: https://gisbi-kim.github.io/world-model-vla-wam-lecture/lecture.html
- Paper guide: https://gisbi-kim.github.io/world-model-vla-wam-lecture/paper-guide.html

## What this repository explains

이 리포는 로봇 지능에서 쓰이는 **world model**, **VLA**, **WAM**이 각각 무엇을 의미하고 서로 어떻게 연결되는지 설명하는 정적 강의 자료이다.

핵심 관점은 world model을 단순한 비디오/장면 생성기가 아니라, 로봇이 세계 상태를 표현하고 행동의 결과를 예측하며 계획에 활용하는 구조로 보는 것이다. 강의문은 renderer, simulator, planner라는 기능적 구분을 바탕으로 VLA를 "시각 관측과 언어 지시에서 행동을 바로 출력하는 policy 중심 모델"로, WAM을 "행동과 그 행동이 만들 미래 세계 변화를 함께 모델링하는 world-dynamics-aware planner"로 정리한다.

따라서 이 리포의 목적은 최신 로봇 foundation model 논의를 논문별 용어 나열로만 소개하는 것이 아니라, World Model -> VLA -> WAM으로 이어지는 개념적 관계와 연구 흐름을 한 번에 읽을 수 있게 정리하는 것이다.

The site is a small static GitHub Pages bundle:

- `index.html`: landing page that lets readers choose the main lecture or the paper guide
- `lecture.html`: original long-form lecture note
- `paper-guide.html`: paper-by-paper guide with reading-order tabs and relationship map

