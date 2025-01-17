# Java Grammar Comprehensive Class 5

## 소개

**Java Grammar Comprehensive Class 5** 프로젝트는 자바 문법 종합반 5주 차 과제로서, 책 목록을 분류하고 조회하는 기능을 구현합니다. 이 프로젝트는 자바의 스트림(Stream) API를 활용하여 책 목록을 다양한 기준으로 필터링하고 정렬하는 방법을 학습하는 데 중점을 둡니다.

## 기능

- **책 목록 분류**: 책 목록을 카테고리별로 분류합니다.
- **가격 필터링**: 특정 가격 이하의 책들을 필터링하여 조회합니다.
- **저자 검색**: 특정 저자의 책들을 검색하여 출력합니다.
- **가격 순 정렬**: 책들을 가격 순으로 정렬하여 출력합니다.

## 설치 및 실행 방법

1. **저장소 클론**: 터미널 또는 명령 프롬프트에서 다음 명령어를 실행하여 저장소를 클론합니다.

   ```bash
   git clone https://github.com/ijieun0123/Java-Grammar-Comprehensive-Class-5.git
   ```

2. **프로젝트 디렉토리로 이동**:

   ```bash
   cd Java-Grammar-Comprehensive-Class-5
   ```

3. **필요한 의존성 설치**: Gradle을 사용하여 의존성을 설치합니다.

   ```bash
   ./gradlew build
   ```

4. **애플리케이션 실행**:

   ```bash
   ./gradlew run
   ```

   또는 생성된 JAR 파일을 직접 실행할 수 있습니다.

   ```bash
   java -jar build/libs/Java-Grammar-Comprehensive-Class-5.jar
   ```

## 클래스 구조

- **Main**: 프로그램의 진입점으로, 사용자 입력을 처리하고 각 기능을 호출합니다.
- **Book**: 책의 정보를 담는 클래스입니다. 제목, 저자, 카테고리, 가격 등의 속성을 가집니다.
- **BookService**: 책 목록을 관리하고, 분류, 필터링, 정렬 등의 기능을 제공합니다.
