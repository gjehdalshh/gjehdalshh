# 💫 About me

- 안녕하세요!  신입 백엔드 개발자 허동민입니다.
- 개발을 접하고 나서 개발하는 재미에 푹 빠져 있습니다.
- 배우고 성장하는 즐거움을 원동력으로 삼고 있습니다.
- 꾸준히 성장하기 위해 새로운 것을 배우고 내 것으로 만들기 위해 노력합니다.
- 함께 성장하기, 커피와 개발을 좋아합니다.  
  
    
    
# 🔎 Profile

### 학력

- 영진전문대학교 컴퓨터공학 전공
- 계명대학교 컴퓨터공학 전공(편입학)

### 자격증

- 정보처리기능사
- 정보처리기사  
  
    
    
# ⚒️ Skills

### langauge
- **Java**,  C,  Python

### Backend
- Java,  Spring MVC,  Git,  AWS,  Linux

### Frontend
- HTML,  CSS,  Javascript  
  
    
    
# 👋 Contact & Channel

- Email ｜ [g](mailto:marketing@wantedlab.com)jehdalshh7@gmail.com
- phone ｜ 010-2757-6511

- Github｜[https://github.com/gjehdalshh](https://github.com/gjehdalshh)
- Blog｜[https://gjehdalshh.tistory.com/](https://gjehdalshh.tistory.com/)  
  
    
    
# Experience

### 2022 한국컴퓨터종합학술대회 (KCC2022)

- 학회에서 연구 성과 발표 및 피드백
- 워크샵을 통한 정보 교류
- 다양한 기업 종사자분들의 코드 리뷰
- https://github.com/gjehdalshh/arduino

### **고문 검색기 외주 작업 (2023)**

- 클라이언트와의 회의를 통한 개발 방향 결정 (프로젝트 범위 결정 및 프로젝트 기간 산정)
- 주 1회 회의를 통해 알맞은 방향으로 개발 중인지 검토
- 호스팅 및 DB  : cafe24, Cloud  storage : AWS S3

- ** 웹 페이지 검색 속도 개선 **
    - 모든 파일에서의 검색 단어 추출 및 단어가 들어간 문단 보여주는 기능
    - S3에 저장된 doc, docx 파일을 모두 가져와 하나의 파일당 하나의 문자열로 추출
    - 추출된 문자열에 해당 검색 단어의 모든 인덱스를 찾고 하나의 문단으로 만들어 보여줌
        1. 단어 검색마다 10만건 데이터 기준 추출 시간 - 20초
            - 페이징 처리를 했지만 페이지를 넘길 때마다 다시 추출 (페이징의 의미가 없음)
            
        2. 첫 검색 후 추출된 데이터를 저장 후 페이징을 통해 보여줌
            - 10만건 데이터 기준 첫 추출 시간 20초
            - 이후 페이지를 넘길 때마다 1초 이내 실행됨
            - 단어 검색마다 첫 추출 시간이 20초나 걸리므로 사용할 수 없음
            
        3. 10만건 데이터를 전부 추출하는 대신 페이징 개수의 기준에 맞춰 페이지를
            
            넘길 때마다일정 개수만 추출
            
            - 페이지마다 일정 개수만 추출하여 보여주기 때문에 모든 페이지가 1초 이내로 실행됨  
              
                
