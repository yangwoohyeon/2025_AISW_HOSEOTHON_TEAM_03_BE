<br>

<div align="center">
 <img width="1026" height="567" alt="image" src="https://github.com/user-attachments/assets/d83dc105-fa8b-4cbb-a5b9-35248997f42e" />
</div>

<h2 align="center">MZ 세대와 시니어 세대간 서로의 관심사에 대한 실시간 퀴즈게임 'GenOn'</h2>

GenOn(제넌)은 MZ 세대와 시니어 세대의 관심사·문화·세대 경험 차이에서 발생하는 갈등을 완화하고,
실시간 퀴즈를 통해 서로를 이해하도록 돕는 세대 간 소통 플랫폼입니다.

GenOn은 1대1 실시간 퀴즈 매칭을 기반으로 양 세대가 상대 세대의 관심사 문제를 풀어가며
서로를 자연스럽게 이해하고 공감할 수 있는 경험을 제공합니다.
<br>

<br>

## ✔️ 주요 기능

### 1. 실시간 1:1 랜덤 매칭
- MZ ↔ 시니어 간 다른 세대끼리만 매칭되도록 설계되었습니다.
- Redis 기반의 큐 매칭으로 빠르고 충돌 없는 매칭을 구현했습니다.
- 매칭 성공 시 즉시 양쪽에 MATCH_FOUND 이벤트가 전송됩니다.

### 2. AI 기반 퀴즈 생성
- OpenAI API를 활용하여 MZ/시니어 세대별 관심사에 맞춘 퀴즈 5문항을 자동 생성합니다.
- 문제·보기·해설이 모두 실시간으로 생성되어 게임마다 새로운 경험을 제공합니다.

### 3. 실시간 WebSocket 게임 진행
- WebSocket 기반 양방향 통신으로 정답 제출, 점수 갱신, 게임 종료까지 완전 실시간 처리.
- 게임 도중 한쪽이 이탈하면 자동으로 기권패 처리되어 공정성을 유지합니다.
- 모든 정답 제출은 즉시 상대에게 반영되어 긴장감 있는 대결 구조를 제공합니다.


  <img width="1497" height="767" alt="image" src="https://github.com/user-attachments/assets/28f3fef3-0c5b-4038-a889-c278ac0dc1b5" />

<br>

## 🎯 목표
- 세대 간 이해 부족으로 발생하는 갈등을 게임 방식으로 자연스럽게 완화하는 것
- 재미 요소를 기반으로 MZ와 시니어가 서로의 관심사를 알아가는 상호작용의 장을 제공하는 것
- 빠른 매칭 및 실시간 소통을 통해 세대 간 공감 경험을 강화하는 것
- 기술을 활용해 세대를 잇는 따뜻한 연결 경험을 제공하는 것


<br>

## 🛠️ 기술 스택
- **Backend**: Spring Boot, JPA, MySQL, WebSocket, Redis  
- **Frontend**: React, TypeScript
- **Infra/DevOps**: AWS EC2, AWS S3, GitHub Actions, Docker  

<br>

## 🧱 서버 아키텍쳐

<img width="1350" height="875" alt="image" src="https://github.com/user-attachments/assets/280295f4-3da8-46ae-a83f-b55567be70aa" />




## 🏆️ 성과

<div align="center">
  <img width="585" height="814" alt="image" src="https://github.com/user-attachments/assets/3a47154e-45f1-4010-940c-a1cc995bc6af" />
</div>


<br>
