<h1 align="center"><strong> PiNest - BackEnd </strong></h1>
<h1 align="center"><img src="https://github.com/SC-PiNest/FrontEnd/blob/master/app/src/main/res/drawable/logo.png" width="300"/></h1>


<div align="center">
  <strong>2024-2 융합소프트웨어프로젝트</strong>
  <br><br>
  <em>스마트 홈 케어 시스템, PiNest (Raspberry Pi + Nest)</em>
  <br><br>
  <em>Written by thatgirls00</em>
</div>

## Description
- 이 프로젝트는 원격으로 실내 환경을 조절하고 관리하며, CCTV를 통해 실시간으로 집 내부를 모니터링할 수 있는 스마트 홈 케어 시스템을 구축하는 것을 목표로 하고 있습니다.
- 또한, 비상 상황 발생 시 즉각적인 알림을 받아 가정의 안전을 강화할 수 있습니다. 이러한 시스템은 1인 가구나 맞벌이 가정 등 현대 사회의 변화하는 주거 환경에 대응하여, 편리함과 안전성을 동시에 제공하는 효율적인 해결책이 될 것입니다.
- 추가적으로, 사용자는 전등이나 가전제품의 작동 시간을 미리 설정하는 예약 기능을 통해, 자동으로 기기를 제어하여 더욱 편리하고 효율적인 생활 환경을 조성할 수 있습니다.

<br>

## Main Function - BackEnd

### 로그인 CRUD 기능
<img width="220" height="500" src="https://github.com/user-attachments/assets/128a0b2a-ebc4-4836-a44f-ded22c72b65d">
<img width="220" height="500" src="https://github.com/user-attachments/assets/f4686467-9267-417d-894e-35572890d897">
<img width="220" height="500" src="https://github.com/user-attachments/assets/76d17c5f-4ccb-4d34-865d-ceaac9dc0d87">

### ID 중복 확인 기능
<img width="220" height="500" src="https://github.com/user-attachments/assets/b9c21de6-12c8-456b-b06d-aebddce508c1">
<img width="220" height="500" src="https://github.com/user-attachments/assets/c2482cb1-6ac6-4453-a572-9d4eff603032">
<img width="220" height="500" src="https://github.com/user-attachments/assets/92506f78-c20f-42a9-a297-4220acc25c53">

- 사용자가 입력한 ID가 데이터베이스에 이미 존재하는지 확인하고, 중복된 ID로 회원가입을 진행하지 못하도록 합니다.
- SHA-256 해시 알고리즘을 통해 비밀번호 암호화 기능 구현 추가하였습니다.

<br>

<!--

### 외부 API 활용하여 GPS에 따라 현재 위치 온습도 확인 
<img width="220" height="500" src="https://github.com/user-attachments/assets/d0bc8cd7-eaed-4898-8fb3-4a375eee57dc">
<img width="220" height="500" src="https://github.com/user-attachments/assets/413ad8ea-7dce-4dea-bac4-f3bda2189b77">
<img width="220" height="500" src="https://github.com/user-attachments/assets/6c64a1cc-346e-4e1d-8f7f-1a9e7ef18ded">

OpenWeather Open API를 활용하여 GPS에 따른 현재 위치에 대한 온습도를 제공합니다.

<br>

### 센서를 통한 실내 온습도 확인 및 추천 기능
<img width="300" height="600" src="https://github.com/user-attachments/assets/747108cb-df38-4a98-ad2d-7fe41f77edb1">
<img width="300" height="600" src="https://github.com/user-attachments/assets/a94eefae-7670-4874-a88d-55c6e4567c53">

Raspberry Pi에 실시간으로 저장되는 온습도 데이터를 불러와 현재 온습도에 맞는 추천 메시지를 출력합니다

<br>

### 원격 CCTV 확인 기능
![Screen_Recording_20241126_164621_PiNest_1](https://github.com/user-attachments/assets/ce8f288b-f701-40c9-afb2-eb185ef72f4f)

Raspberry Pi를 통해 원격으로 실내의 CCTV 스트리밍을 실시간으로 확인 기능을 구현합니다

<br>

### 원격 전등 On/Off 기능
<img width="300" height="600" src="https://github.com/user-attachments/assets/c07abbef-a688-4b0b-8ef8-bb858ce899f5">
<img width="300" height="600" src="https://github.com/user-attachments/assets/33e8604d-d952-4e9f-96f6-1ffb9ec29021">

Raspberry Pi를 통해 원격으로 서보 모터를 제어하여 전등 스위치를 on/off 하는 기능을 구현합니다

<br>

### 감시모드 및 On/Off 기능

-->

## Roles in Charge

<div sytle="overflow:hidden;">
<table>
  <tr>
    <td colspan="1" align="center"><strong>BackEnd</strong></td>
    <td colspan="2" align="center"><strong>FrontEnd</strong></td>
      <td colspan="1" align="center"><strong>Hardware</strong></td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/thatgirls00"><img src="https://avatars.githubusercontent.com/u/109068985?v=4" width="150px;" alt="전현수"/><br/><sub><b>전현수</b></sub></a>
    </td>
    <td align="center">
      <a href="https://github.com/1ShinSuHo1"><img src="https://avatars.githubusercontent.com/u/67681246?v=4" width="150px" alt="신수호"/><br/><sub><b>신수호</b></sub></a>
    </td>
    <td align="center">
      <a href="https://github.com/joon6390"><img src="https://avatars.githubusercontent.com/u/184930643?v=4" width="150px" alt="박해준"/><br/><sub><b>박해준</b></sub></a>
    </td>
    <td align="center">
      <a href="https://github.com/Hooie"><img src="https://avatars.githubusercontent.com/u/67465736?v=4" width="150px" alt="이태호"/><br/><sub><b>이태호</b></sub></a>
    </td>
  </tr>
</table>

> 전현수 : Spring API 서버 개발 / AWS EC2 서버 및 RDS(MySQL) 구축 / CRUD 기능 구현 <br><br>
> 신수호 : BackEnd와 통신 및 Android Studio 개발 / Firebase 서버 구축 <br><br>
> 박해준 : HardWare와 통신 및 Android Studio 개발 / 앱 UI/UX 디자인 <br><br>
> 이태호 : Raspberry Pi 개발
</div>
<br>

## Architecture
![SC project 3-2 (8)](https://github.com/user-attachments/assets/dc192d9f-38df-45d8-9896-989915b04473)


## Tech Stack
<div>
    <table>
        <tr>
            <td colspan="2" align="center">
                Language
            </td>
            <td colspan="4">
                <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=openjdk&logoColor=white">
                <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                Framework
            </td>
            <td colspan="4">
                <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/>
                <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                API
            </td>
            <td colspan="4">
                <img src="https://img.shields.io/badge/OpenWeather Open API-0054A3?style=for-the-badge&logo=nginx&logoColor=white"> 
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                Server
            </td>
            <td colspan="4">
                <img src="https://img.shields.io/badge/amazon ec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> 
                <img src="https://img.shields.io/badge/Firebase-BF0000?style=for-the-badge&logo=firebase&logoColor=white"/>
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                Database
            </td>
            <td colspan="4">
                <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white">
                <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                Tool
            </td>
            <td colspan="4">
                <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
                <img src="https://img.shields.io/badge/Android Studio-6DB33F?style=for-the-badge&logo=Android Studio&logoColor=white"/>
            </td>
        </tr>
        <tr>
          <td colspan="2" align="center">
                Hardware
            </td>
            <td colspan="4">
                <img src="https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi&logoColor=white"> 
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                etc.
            </td>
            <td colspan="4">
                <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=GitHub&logoColor=white"/>
                <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">
                <img src="https://img.shields.io/badge/FileZilla-BF0000?style=for-the-badge&logo=FileZilla&logoColor=white">
                <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">
            </td>
        </tr>
    </table>
</div>

<br>
