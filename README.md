## 뇌파 데이터를 이용한 시각화 프로젝트

### Introduction
- 본 문서는 Windows 10 환경에서 Python으로 MindWave Mobile 2 장비로부터 뇌파 정보를 받는 방법을 소개 (Mac은 Python의 bluetooth module이 잘 설치되지 않음)
- 장비가 수집하는 뇌파
    1. attention/concentration (집중도)
    1. meditation/relaxation (이완도)
    1. raw EEG data (delta, highAlpha, highBeta, lowAlpha, lowBeta, lowGamma, midGamma, theta)
- 작동원리
    1. MindWave Mobile 2
    - bluetooth를 통해 컴퓨터와 통신
    1. Philips HUE
    - wifi를 통해 컴퓨터와 통신
    - wifi 공유기에 HUE Bridge를 연결(컴퓨터에서는 Bridge가 연결된 wifi를 잡아야한다.)
    - Bridge와 전구가 연결되어 상호 통신

### 준비물
- Mindwave Mobile 2
- Philips HUE
- Windows 운영체제
- 사용 언어: python

### 개발 단계
1. [Python으로 MindWave Mobile 2 뇌파 데이터 받아오기](https://gyutaepark278.github.io/mindwave.md)
2. [뇌파 데이터를 HUE로 표현하기](https://gyutaepark278.github.io/hue.md)
