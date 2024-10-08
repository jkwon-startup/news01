# news01
파이썬강의용
# 네이버 뉴스 크롤러

이 프로젝트는 Streamlit을 사용하여 네이버 뉴스를 크롤링하고 결과를 워드 문서로 다운로드할 수 있는 웹 애플리케이션입니다.

## 설치 방법

1. 저장소를 클론합니다:
   ```
   git clone https://github.com/jkwon-startup/news01.git
   cd your-repository
   ```

2. 필요한 패키지를 설치합니다:
   ```
   pip install -r requirements.txt
   ```

## 실행 방법

다음 명령어로 애플리케이션을 실행합니다:

```
streamlit run app.py
```

브라우저에서 `http://localhost:8501`을 열어 애플리케이션에 접속합니다.

## 사용 방법

1. 검색할 키워드를 입력합니다.
2. 가져올 기사 수를 선택합니다.
3. "뉴스 검색" 버튼을 클릭합니다.
4. 결과를 확인하고 "다운로드" 버튼을 클릭하여 워드 문서로 저장합니다.

## 주의사항

이 애플리케이션은 교육 및 개인 사용 목적으로만 사용해야 합니다. 웹 스크래핑 시 해당 웹사이트의 이용 약관을 준수해야 합니다.