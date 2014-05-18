## 쉬운 스프링 이야기
### 2014.05.14

##### http://spring.io
##### http://okjsp.tistory.com/tag/shortcut 
####  개발환경
 * 브라우저
    * 크롬브라우저  http://www.google.com/chrome
 * java 7
    * http://java.sun.com
 
 * 환경변수 %JAVA_HOME%\bin;
 * 패스변수
 * 자바 홈 확인 : echo %JAVA_HOME%
 * Spring 3.x
    * Spring 4.0 (jdk1.8)
 * sts(Spring Tool Suite)
 * 스프링개발도구
    * http://spring.io/tools/sts/all 
 * 스프링개발도구설치
    * C:\Users\funnywork\java\Documents\sts-3.5.1.RELEASE
 * STS.ini 파일에 추가
    * -Dfile.encoding=utf-8
 * workspace 
    * C:\Users\funnywork\java\workspace-sts 
 * 톰캣설치(자바웹서버)
    * http://tomcat.apache.org
    * 설치위치 : C:\Users\funnywork\java\apache-tomcat-7.0.53
 * zip 다운로드 (반디집-알아서풀기)
    *  http://www.bandisoft.co.kr/bandizip/
 * 무료캡처 프로그램
    * www.picpick.org/kr  
 
#### 스프링역사

- - -

## git 시작하기
#### 설치 및 가입
 * git 가입하기
    *  https://github.com/

#### 테스트 작업 (git 클라이언트 실행 후)
 * pwd (현재위치)
 * whoami (나는누구?)
 * mkdir git  (git 디렉토리 생성)
 * git clone https://github.com/ikinox/ikidev.git 
    * (git hub 에서 생성한 공유 디렉토리 주소 연결해서 서버에 있는 자료를 로컬로 받아옴)
 * explorer . 
 * ikidev 디렉토리내에 spring 디렉토리 생성
 * cd ikidev/spring 이동
 * touch spring.md (spring.md 파일을 하나 만듬)
    * 파일 내용 작성... 예) 스터디 내용 작성
 * cd .. (ikidev 디렉토리로 이동)
 * git status
    * spring/ (스프링이랑는 폴더가 생겼음...) 
 * git add spring
 * git status
    * spring/ 에 spring.md 파일이 추가 됨
 * git commit -m "spring doc start"
    * Please tell me who you are. (당신은 누구?)
    * run
    * git confing --global user.email "you@example.com" (이메일 입력)
    * git config --global user.name "your name" (이름 입력)
 * 위메세지 내용은 github 접속계정 정보를 입력해야 github에 파일을 커밋 할수 있음.
    *  git config --gloval user.email ikinox@naver.com  (따옴표는 필요없음)
    *  git config --gloval user.name ikinox
 * git commit -m "spring doc start"
 * git status
    * Onbranch master (현재 브랜치는 마스터 브랜치) 
 * git remote -v
    - 현재 origin alias 에는 https://github.com/ikinox/ikidev.git 로 되어 있음
    * origin  https://github.com/ikinox/ikidev.git (fetch) (가져오기 주소)
    * origin  https://github.com/ikinox/ikidev.git (push) (보내는 주소)
 * git push origin master (서버로 보냄)
    * Username for 'https://github.com': ikinox (이름)
    * Password for 'https://ikinox@github.com' : 패스워드
    * Counting objects: 5, done.
    * Delta compression using up to 4 threads.
    * Compressing objects: 100% (3/3), done. | 0 bytes/s, done.
    * Writing objects: 100% (4/4), 1.38 KiB
    * Total 4 (delta 0), reused 0 (delta 0)
    * To https://github.com/ikinox/ikidev.git
    *   f341480..fd66900  master -> master
 * 올려진 파일 계정에서 확인 (올려진 파일 주소)
    * ttps://github.com/ikinox/ikidev/blob/master/spring/spring.md#github 
 * 

#### git 관련 오류
###### Git Client 사용중 curl_multi_timeout 및 libcurl.dll 에러
 * libcurl.dll 다운받아 C:\Windows\System32 위치에 덮어쓰고 윈도우 재시작 하면 대부분 해결됨.
 * google.com 에서 libcurl.dll windows 7 검색 후 조치 함.
 
- - -

## github
#### 가입 및 사용
 * http://github.com
 * 셋업
    * https://github.com/ikinox/ikidev.git 
 * 
  
## Source tree (사용법 : )

## 슬라이드쉐어
#### http://www.slideshare.net
 * spring 3 검색 : 여러 슬러이드 자료 볼수 있음
 * http://www.slideshare.net/kenu


