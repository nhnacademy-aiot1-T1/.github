# 🏭 AIOTONE - 머신러닝을 활용한 모터 이상감지 시스템
<p align="center">
  <img src="https://github.com/nhnacademy-aiot1-T1/.github/assets/80664194/30b941a0-ace2-4eba-bc15-66f76bca5b93" height="500" alt="text" />
</p>

<table align="center">
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/AoiTuNa"><img src="https://avatars.githubusercontent.com/u/118845947?v=4"width="100px;" alt=""/><br /><sub><b>홍충표</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/jki12"><img src="https://avatars.githubusercontent.com/u/129145278?v=4" width="100px;" alt=""/><br /><sub><b>조강일</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/chanhwiim"><img src="https://avatars.githubusercontent.com/u/101960840?v=4" width="100px;" alt=""/><br /><sub><b>임찬휘</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/ckddms6530"><img src="https://avatars.githubusercontent.com/u/121488797?v=4" width="100px;" alt=""/><br /><sub><b>유창은</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/pangpangE123"><img src="https://avatars.githubusercontent.com/u/134940639?v=4" width="100px;" alt=""/><br /><sub><b>변상우</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/qaw302"><img src="https://avatars.githubusercontent.com/u/80664194?v=4" width="100px;" alt=""/><br /><sub><b>박미정</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

<br />
<br />
<br />  

## 🪧 프로젝트 소개
> 모터와 관련된 센서 데이터를 모니터링할 수 있는 웹 서비스와, <br/>
> 센서 데이터를 바탕으로 AI를 활용하여 모터 상태를 진단하고 이상이 발생했을 때 알림을 받을 수 있는 시스템입니다

### 주요기능 <br />
  ➡️ 전체 공간에 대한 모터 상태 모니터링 기능 <br />
  ➡️ 모터 별 데이터 현황 모니터링 기능 <br />
  ➡️ AI를 활용한 모터 상태 관리 <br />

### Repository Tree
AIOTONE<br>
├── Web<br>
│         ├── [front-server](https://github.com/nhnacademy-aiot1-T1/front-server) : Front API 서버<br>
│         ├── [gateway-server](https://github.com/nhnacademy-aiot1-T1/gateway-server) : 요청 인증/인가 및 API 라우팅 서버<br>
│         ├── [service-discovery](https://github.com/nhnacademy-aiot1-T1/service-discovery) : Eureka 서버<br>
│         ├── [auth-server](https://github.com/nhnacademy-aiot1-T1/auth-server) : 인증 API 서버<br>
│         ├── [account-api](https://github.com/nhnacademy-aiot1-T1/account-api) : 계정 API 서버<br>
│         └── [monitoring](https://github.com/nhnacademy-aiot1-T1/monitoring) : 모니터링 API 서버<br>
└── RuleEngine<br>
             ├── [preprocessing](https://github.com/nhnacademy-aiot1-T1/preprocessing) : 전처리 서버<br>
             ├── [machine-learning-server](https://github.com/nhnacademy-aiot1-T1/machine-learning-server) : 머신러닝 서버<br>
             ├── [simple-telegraf](https://github.com/nhnacademy-aiot1-T1/simple-telegraf) : 데이터 수집(telegraf 역할)<br>
             ├── [adc-gateway](https://github.com/nhnacademy-aiot1-T1/adc_gateway) : 모터 데이터 수집 
             └── [notification](https://github.com/nhnacademy-aiot1-T1/notification) : 알림/이메일 전송 서버<br>
<br />
<br />

## 🏛 아키텍처 
### 시스템 구조
![2024-06-04 23_35_08 144](https://github.com/nhnacademy-aiot1-T1/.github/assets/80664194/400d5f9f-76b9-484f-84ef-01fd4e310399)

<br/>
<br/>

### CI/CD
![2024-06-04 23_38_59 099](https://github.com/nhnacademy-aiot1-T1/.github/assets/80664194/73b26716-64f8-449b-ad93-08b3dd620f44)



## ⚙ 기술 스택
### Language
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat&logo=Thymeleaf&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white)
![Java](https://img.shields.io/badge/Java-E34F26?style=flat&logo=Java&logoColor=white)
![python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)

### Framework
![Spring](https://img.shields.io/badge/spring-6DB33F?style=flat&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/spring%20boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/spring%20security-6DB33F?style=flat&logo=springsecurity&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/spring%20cloud-3693F3?style=flat&logo=googlecloud&logoColor=white)
![Spring Gateway](https://img.shields.io/badge/spring%20gateway-3693F3?style=flat&logo=googlecloud&logoColor=white)
![Spring Eureka](https://img.shields.io/badge/spring%20eureka-3693F3?style=flat&logo=googlecloud&logoColor=white)
</br>
![SpringDataJPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat&logo=Spring&logoColor=white)

### Database
![MySQL](http://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white)
![InfluxDB](https://img.shields.io/badge/influxdb-22ADF6?style=flat&logo=influxdb&logoColor=white)

### Build Tool
![ApacheMaven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=ApacheMaven&logoColor=white)

### CI/CD
![Github Action](https://img.shields.io/badge/Github%20Action-2088FF?style=flat&logo=githubactions&logoColor=white)
![NHN Cloud](https://img.shields.io/badge/-NHN%20Cloud-blue?style=flat&logo=iCloud&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E98CD?style=flat&logo=SonarQube&logoColor=white)

### ETC
![intellijidea](https://img.shields.io/badge/intellij-000000?style=flat&logo=intellijidea&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white)
##
- 개발기간 : 2024.03.25 ~ 2024.06.05
