🍴 Foodsite - 오늘 뭐 먹었지? 기록장
오늘 먹은 음식을 기록하고 관리하는 웹 애플리케이션입니다.
맛있었던 음식, 별로였던 음식 모두 기록해두고 나중에 찾아볼 수 있어요.

🛠 사용 기술

- Java 21
- Spring Boot
- Thymeleaf (화면 구성)
- MyBatis (DB 연동)
- Oracle DB (데이터 저장)
- Bootstrap 5 (디자인)
- Gradle (빌드 도구)

📁 프로젝트 구조

foodsite
├── src/main/java/com/pknu26/foodsite

│   ├── controller/FoodController.java   # 요청 처리

│   ├── dto/Food.java                    # 데이터 클래스

│   ├── mapper/FoodMapper.java           # DB 연동 인터페이스

│   └── FoodsiteApplication.java         # 실행 진입점

├── src/main/resources

│   ├── mapper/FoodMapper.xml            # SQL 쿼리

│   ├── templates/food                   # 화면 HTML

│   │   ├── list.html                    # 목록

│   │   ├── addForm.html                 # 추가

│   │   └── editForm.html               # 수정

│   └── application.properties           # 설정 파일

└── build.gradle                         # 의존성 관리
