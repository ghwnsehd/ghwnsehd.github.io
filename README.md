# 🤖 ghwsnehd | 로봇 소프트웨어 엔지니어 포트폴리오

안녕하세요! 하드웨어와 소프트웨어를 연결하여 문제를 해결하는 데 가치를 두는 **로봇 소프트웨어 엔지니어** 지망생 ghwsnehd입니다. 
주로 **C++**과 **ROS2**를 활용하여 로봇의 인지 및 제어 알고리즘을 연구하고 기록합니다.

---

## 🛠️ 기술 스택 (Tech Stacks)
* **Languages**: C++, Python
* **Frameworks & Tools**: ROS2 (Humble), Git/GitHub
* **Simulators**: Gazebo, Webots

---

## 🚀 프로젝트 요약 (Featured Project)

### 📌 프로젝트명: ROS2 기반 2자유도 로봇 팔 기구학 제어 및 시각화
> **개발 기간**: 2026.10 ~ 2026.11 (개인 프로젝트)
> **핵심 역할**: 역기구학(Inverse Kinematics) 수식 구현 및 RViz 데이터 시각화


#### 💡 주요 구현 내용 및 트러블슈팅
1. **역기구학 수식 직접 구현**: 외부 라이브러리 없이 기하학적 접근법을 사용하여 C++로 로봇 관절 각도를 정밀하게 산출하는 알고리즘 작성.
2. **좌표계(TF) 오류 해결 (Troubleshooting)**: 
   * **문제**: 모터 가동 시 RViz 상에서 로봇 팔의 관절 링크 좌표계가 틀어지는 오류 발생.
   * **원인**: `robot_state_publisher` 노드 등록 시 조인트 각도 행렬 변환 오차 누적 확인.
   * **해결**: 복합 변환 행렬 연산 루틴을 쿼터니언(Quaternion) 구조로 리팩토링하여 연산 오차 제거 후 안정적인 추적 성공.

---

## 📝 최근 학습 및 에러 로그 (Core Logs)
* [2026-11-04] ROS2 Action 통신을 활용한 로봇 목표 지점 이동 제어 구현
* [2026-10-28] CMakeLists.txt 빌드 에러 및 외부 라이브러리 링크 문제 해결 과정

---

## 📫 Contact
* **GitHub**: [https://github.com](https://github.com)
* **Email**: 이메일 주소를 입력하세요.
