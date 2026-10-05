# Aeri Kim

로봇을 직접 조립하고, 실제로 움직이게 만드는 일을 좋아합니다.
문제가 생기면 측정으로 원인을 찾아 해결될 때까지 파고들고, 그 과정을 문서로 남깁니다.

TurtleBot3 다중 로봇 자율주행, FR5 협동로봇 디지털 트윈과 비전 조립, SO-ARM101 두 대 분산 제어,
LeKiwi 모바일 매니퓰레이터를 만들었습니다. 팀 프로젝트에서는 주로 로봇 제어 · 비전 · 하드웨어를 맡았습니다.

### 기술 스택

<p>
  <img src="https://skillicons.dev/icons?i=python,cs,cpp,c,ros,unity,opencv,pytorch,raspberrypi,arduino,linux,bash,git" alt="Python, C#, C++, C, ROS2, Unity, OpenCV, PyTorch, Raspberry Pi, Arduino, Linux, Bash, Git" />
</p>

| 분야 <img src="docs/images/layout/w400.png" width="100%" height="1"> | 내용 <img src="docs/images/layout/w2600.png" width="100%" height="1"> |
| --- | --- |
| Robotics | ROS 2 (Jazzy / Humble) · Nav2 · SLAM · AMCL · MoveIt2 · TF2 / URDF · CycloneDDS · LeRobot · Fairino FR5 SDK |
| Language | Python · C# (Unity) · Arduino C · Bash · C++ (기초) |
| Vision | OpenCV · ArUco · RealSense D435 (RGB-D) · 카메라 캘리브레이션 · YOLO · 비전-모션 연동 |
| Hardware / Control | Raspberry Pi · Arduino · UART · GPIO / PWM · 모터 · 엔코더 · IMU · DYNAMIXEL XL430 · STS3215 버스 서보 · Modbus-RTU |
| Tools | Linux · Git / GitHub · Unity · TCP / UDP · ZeroMQ · Flask · Three.js · Jira / Confluence · Slack |

### 협업 툴

<p>
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />
  <img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white" alt="Confluence" />
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" alt="Slack" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

## 프로젝트

[smart-factory-make-home-team-](https://github.com/kimar1022-code/smart-factory-make-home-team-) - FR5 · ZeKeep 협동로봇이 조립식 주택을 만드는 로봇셀. 4인 팀 프로젝트에서 로봇 제어 · 비전 보정 · 서버 인터페이스 담당.
힘 센서도 지그도 없이 카메라 2대(RealSense D435 · RGB)만으로 밑판을 측정하고 벽을 정렬해 삽입.
벽 5장 전량 삽입, 파지 재현 오차 1.7mm → 0.13mm, 문서 없는 PLC 로봇을 MODBUS로 직접 붙여 반복 정밀도 0.55mm.

[lerobot-lekiwi-mobile-manipulator](https://github.com/kimar1022-code/lerobot-lekiwi-mobile-manipulator) - 옴니휠 베이스 + SO-101 팔인 LeKiwi를 직접 조립해 리더팔 원격 조종, 웹 관제(카메라 3대 + 3D 디지털 트윈)까지 구축.
OpenCV · ArUco만으로 색 블록을 스스로 찾아 집고 보관함에 넣는 자율 집기 구현.
팔은 가르친 자세만 쓰고 위치 정렬은 옴니휠로 맡겨, 역기구학 없이 3회 연속 성공.

[turtlebot3-ai-safety-patrol](https://github.com/kimar1022-code/turtlebot3-ai-safety-patrol) - TurtleBot3 3대가 물류센터를 무인 순찰하는 5인 팀 프로젝트에서 자율주행 파트와 하드웨어 확장 담당.
순찰 FSM, ±2mm 정밀 충전 도킹, 배터리 기반 2대 자동 교대까지 실기 검증.
지게차 리프트(3D 프린팅 랙앤피니언)와 마그네틱 포고핀 충전 단자도 직접 제작.
주행 성공률 30%를 100%로 끌어올린 문제 해결 기록을 함께 담았습니다.

[autonomous-exploration-robot](https://github.com/kimar1022-code/autonomous-exploration-robot) - 키트가 아니라 직접 만든 4WD 로봇을 ROS2에 연결하는 개인 프로젝트.
모터 · 엔코더 · IMU 펌웨어부터 UART 프로토콜, odometry, LiDAR까지. SLAM/Nav2 올리는 중.

[fairino-fr5-digital-twin](https://github.com/kimar1022-code/fairino-fr5-digital-twin) / [v2](https://github.com/kimar1022-code/fairino-fr5-digital-twin-v2) - 산업용 협동로봇 FR5와 Unity를 실시간 동기화하는 디지털 트윈.
DLS Jacobian IK 직접 구현, Mirror 동기화 패턴. v2는 UI를 16개 패널로 모듈화하고
PLC 티칭 · 웨이포인트 녹화/재생을 추가한 재설계 버전.

[smart-factory-soarm101](https://github.com/kimar1022-code/smart-factory-soarm101) - SO-ARM101 협동로봇 2대를 LeRobot SDK + 라즈베리파이 + Unity로 분산 제어.
TCP/JSON 프로토콜 직접 설계. 글로벌캠이 위치를 찾고 손목캠이 마지막 정렬을 맡는
2단계 비전으로 색 블록을 집어 접시에 분류.

## 연락처

kimar1022@gmail.com
