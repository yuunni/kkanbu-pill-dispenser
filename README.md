# 시연영상
[![Watch the video](https://img.youtube.com/vi/z6HVQ2MKFn4/hqdefault.jpg)](https://www.youtube.com/watch?v=z6HVQ2MKFn4)
-------------------------
# 2022 서울 하드웨어 해커톤 '깐부'팀 : 포스트 코로나 시대에 맞춘 비대면 진료 및 약 처방 시스템
- **[오정민](https://github.com/owjs3901)(팀장 - HW/SW 개발자)**
> 프로젝트 매니저<br />
> 기획 및 개발 검토

- **[임동연](https://github.com/yeon-dong)(팀원 - SW 개발자)**
> 하드웨어 제작 및 STM32 Setting<br />
> 기획 및 개발

- **[서윤재](https://github.com/yuunni)(팀원 - HW 개발자)**
> STM32 코드 작성, README.md<br />
> 센서, 핀 설계 및 연동

![Alt text](/img/member.jpg)
# 개요
포스트 코로나 시대에 맞춘 비대면 진료 및 약 처방 장치를 개발하였다. <br />
이를 통하여 시각장애인이나 노인 등 병원에 가기 힘든 상황의 사람들에게 간편한 진료 및 약 처방을 제공한다. <br />
약을 정해진 시간에 나오게 하여 잊어버리지 않도록 하는 기능이 존재한다. <br />

![Alt text](/img/image2.jpg)

# Specification
* STM32<br />
* Servo motor<br />
* Infrared Motion Sensor HC-SR501<br />
* LED<br />

![Alt text](/img/image.jpg)

# 기능
* 서보 모터를 통한 약 투여<br />
* 약 전달의 하드웨어적 구현<br />
* 센서를 통한 모션 감지<br />
* 동작 시 LED 알림<br />

# 주요 코드

파일명|내용
---|---
main.c|main code

# 구현사항
* Peripheral GPIO : 적외선 모션 감지 센서, LED<br />
* PWM : Servo motor

# Once apon a time...
[![Watch the video](https://img.youtube.com/vi/CrS39qecWtI/hqdefault.jpg)](https://www.youtube.com/watch?v=CrS39qecWtI)
