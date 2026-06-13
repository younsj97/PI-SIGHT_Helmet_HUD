# PI-SIGHT Helmet HUD

PI-SIGHT Helmet HUD는 헬멧 외부에 장착하여 사용자의 눈앞에 필요한 정보를 표시하는 헤드 업 디스플레이 장치 입니다. 사용자는 고개를 움직이지 않고도 눈앞의 디스플레이를 통해 필요한 정보 또는 후방카메라 영상을 확인할 수 있습니다.

기기의 가장 큰 특징은 소형 범용 컴퓨터인 라즈베리 파이와 교체식 모듈 시스템을 적용했다는 것입니다. 이를 통해 사용자가 직접 소프트웨어를 프로그래밍하거나 필요한 소프트웨어로 교체할 수 있고, 블루투스 헤드셋이나 GPS 모듈을 연결해 내비게이션, 레이싱 계측기, 항공 계기판 등 다양한 용도로 사용할 수 있습니다.


## 기능

 - 프리즘 디스플레이 : 눈앞에 위치한 3000cd/m^2 디스플레이를 통해 고개를 움직이거나 별도의 기기를 거치하지 않아도 필요한 정보를 확인할 수 있음
 - 범용 시스템 : 범용 리눅스 컴퓨터인 라즈베리파이를 사용해 목적에 맞는 프로그램과 센서를 쉽게 개발하여 적용할 수 있음
 - 교체형 모듈 시스템 : 프로그램과 모듈을 쉽게 교체할 수 있도록 하여 한 대의 기기를 다양한 활동에서 사용할 수 있음
 - 무선 리모컨, 후방 카메라 등 자세한 내용은 [VUDEV 웹사이트](https://sites.google.com/vudev.net/vudevnet/about-pi-sight) 또는 [설명서](https://github.com/younsj97/PI-SIGHT_Helmet_HUD/blob/main/PI-SIGHT%20%EC%82%AC%EC%9A%A9%EC%84%A4%EB%AA%85%EC%84%9C-1%20(%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4%20%EA%B8%B0%EB%B3%B8).pdf)를 다운로드하여 확인하세요


## 소프트웨어

 1. [Openauto](https://github.com/younsj97/PI-SIGHT_SW_Openauto) : 안드로이드 스마트폰과 연결해 안드로이드 오토 헤드 유닛으로 사용할 수 있습니다.
 2. [GPS Racer](https://github.com/younsj97/PI-SIGHT_SW_GPSRacer) : 자체 랩타이머 또는 스마트폰 연동 블루투스 GPS 수신기로 사용할 수 있습니다.
 3. [Rearview](https://github.com/younsj97/PI-SIGHT_SW_Rearview) : 실시간 후방 카메라 영상을 보여주며, 작동 중 자동으로 녹화됩니다.
 - 누구든지 필요한 프로그램과 모듈을 제작해 사용할 수 있습니다.


## 제작 방법

 - [제작 영상](https://youtu.be/Ew3B-dukdHQ?si=9M7wGLM0dlpmkkXc)과 [회로도](https://github.com/younsj97/PI-SIGHT_Helmet_HUD/blob/main/Documents/Circuits.pdf)를 참고하세요.


## 주의사항

 - _PI-SIGHT는 다양한 환경에서 충분한 테스트를 거치지 않았습니다. 제작과 사용은 자유지만, 그로 인해 발생하는 문제에 대하여 책임지지 않습니다._
 - _PI-SIGHT는 방진,방수를 지원하지 않습니다. 물이 들어가지 않도록 하세요_
 - _프리즘 디스플레이의 텐션 조절 볼트가 너무 느슨하면 사용 중 디스플레이가 움직여 위험할 수 있습니다_


## 커스터마이징

 - 무선 리모컨 펌웨어는 [PI-SIGHT Remote Controller SW](https://github.com/younsj97/PI-SIGHT_SW_RemoteController)를 참고하세요
 - PCB 회로 및 모듈 커넥터는 [회로](https://github.com/younsj97/PI-SIGHT_Helmet_HUD/blob/main/Documents/Circuits.pdf) 자료를 참고하세요
