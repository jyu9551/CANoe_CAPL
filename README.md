#  주제 : '제어기 진단 통신 기능' 동적 검증 자동화 프로젝트 (CANoe, CAPL)

## 프로젝트 소개
1.	ECU의 진단 통신 관련 요구사양서를 분석하여 동적 검증 및 자동화하는 프로젝트<br><br>
<img src="https://github.com/user-attachments/assets/2503c11f-3592-4982-8f9e-f5237755e49a" width="65%" height="65%"> <br><br>

## Vector CANoe 기반 Architecture
<img src="https://github.com/user-attachments/assets/f625a4a2-7732-46b2-8526-c1c35b48c7ce" width="79%" height="79%"><br><br>


## 1️⃣ Global Path Planning
Global Path Planning을 위한 경로 탐색 알고리즘 비교 후 A star 알고리즘 적용<br><br>
<img src="https://github.com/user-attachments/assets/fb25a0ac-b8d4-413f-bd17-0048b65ffc73" width="40%" height="40%">

## 2️⃣ Driving
<table>
  <tr>
    <td width=45%>
    [Local Path Planning]<br>
    1. Catesian to Frenet Frame<br>
    2. Make Path List<br> 
    3. Make Obstacle List<br>
    4. Decision Path<br>
    5. Frenet to Catesian Frame<br>
    6. Catesian to GlobalFrame<br><br>
    <br>[Driving Control]<br>
    1. PD Speed Control<br>
    2. Pure Pursuit Steering Control<br></td>
    <td>
    <img src="https://github.com/user-attachments/assets/dbe79140-e5d9-492e-b744-44bad299327b" width="95%" height="95%" align="center">
    </td>
  </tr>
</table>

## 3️⃣ Parking
<img src="https://github.com/user-attachments/assets/90c29945-feaf-4cf2-99a7-958797673dd1" width="40%" height="40%">


## 시연영상
https://youtu.be/TwMqGNApJog
