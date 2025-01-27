# Clock_for_Everyone (모두의 시계)
- Project Period : 2019.4.5 ~ 2019.11.22

<br>

### 프로젝트 소개 및 주요기능
- 하나의 디바이스로 다양한 정보 전달 매개체인 "모두의 시계"를 개발하는 프로젝트
- 모두의 시계는 점자 축으로 시간 정보를 제공하는 촉각부와 청각으로 생활정보를 제공하는 스피커부, 시각을 제공하는 Edge부로 구성됨
- 기존 시계는 장애가 있는 사용자가 이용할 수 있는 기능이 제한되는 경우가 있으며 비장애인도 시간 확인이 어려운 어두운 상황 등에서 시간 확인의 필요성을 느낌

<br>

### 작품의 특징 및 장점
- 모두의 시계는 방향성을 가지는 디바이스로 회전을 통하여 각기 다른 기능을 활성화 시킬 수 있음
- 촉각부는 점자 형태로 이루어져 있으며 돌출되는 돌기의 개수로 시간을 이해할 수 있는 인터페이스를 사용, 사용자 편의에 따라 스피커부와 Edge 디스플레이 중 추가 기능을 선택적으로 사용 가능함
- 촉각부의 점자 축의 종단에는 LED가 내장된 형태로 디바이스 회전을 통해 Edge 디스플레이가 활성화 되면 LED 또한 발광하여 활성화 여부를 알 수 있음
- Edge에는 다양한 생활 정보를 제공하며 사용자 움직임이 인식되면 활성화되며 활성화 시에는 백라이트를 활용하여 정보전달이 원활하도록 함
- 모두의 시계는 인터넷을 활용하여 날씨, 온습도, 바람의 세기, 미세먼지 농도 등의 생활정보를 수집하여 사용자에게 전달함
- 별도의 어플리케이션 연동이나 복잡한 설치의 과정을 요구하지 않으며, 가벼운 소재의 케이싱으로 이동 및 보관에 편리하게 제작


| <img src="https://github.com/user-attachments/assets/c490877e-1f9e-41cd-ae58-bdd5edcfa0bf" alt="모두의 시계" width="300"> <img src="https://github.com/user-attachments/assets/7749c975-81bd-475e-bede-39ee257ec833" alt="모두의 시계_후면" width="300">| <img src="https://github.com/user-attachments/assets/027de6f1-740d-447c-83ea-18aa986712ce" alt="모두의 시계 축" width="300"> | 
|:------:|:-----:|
| **모두의 시계 전면, 후면** | **모두의 시계 점자 축** |


| <img src="https://github.com/user-attachments/assets/cb75d62d-15ca-4e39-b696-6d2ace97d982" alt="모두의 시계 설명" width="450"> | <img src="https://github.com/user-attachments/assets/864c26ac-2f9c-4e59-a2d6-6899012cab4d" alt="7시 35분" width="350"> | <img src="https://github.com/user-attachments/assets/361136a4-f767-44f9-a164-6b5e10d806ac" alt="17시 45분" width="350"> |
|:-----:|:-----:|:-----:|
| **모두의 시계 점자부** | **7시 35분을 나타내는 예시** | **17시 45분을 나타내는 예시** |

<br>

### 프로젝트 개발환경
#### SW 개발환경
- Arduino IDE : 프로그램 편집 및 컴파일, 업로드
- Cadence OrCAD 15.6 : 하드웨어 내 PCB 제작을 위한 artwork 작업
- Allegro PCB Designer : OrCAD 내 기본 부품 외 부품 파일을 생성
- Inventor 2019 : 시계의 케이싱 작업 및 결과물 확인을 위한 3D 모델링
- 개발 언어 : Arduino C, Python

#### HW 구성장비
- Arduino Mega : GPIO 
- RTC, 스마트모터, ESP8266 등 기능 구성용 센서
  
