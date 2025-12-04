# 태양흑점 데이터 분석 대시보드

Streamlit을 사용한 태양흑점 데이터 시각화 대시보드입니다.

## 기능

- 시계열 라인 차트
- 히스토그램 및 커널 밀도 추정
- 상자 그림 (1900-2000년)
- 산점도 및 추세선

## 인터랙티브 기능

- 연도 범위 선택
- 히스토그램 구간 수 조절
- 추세선 차수 조절
- 산점도 점 크기 조절
- 산점도 투명도 조절

## 로컬 실행 방법

1. 가상환경 생성 (선택사항):
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

2. 패키지 설치:
```bash
pip install -r requirements.txt
```

3. Streamlit 앱 실행:
```bash
streamlit run Question3.py
```

## Streamlit Cloud 배포

1. GitHub 저장소에 코드 푸시
2. [Streamlit Cloud](https://streamlit.io/cloud)에서 새 앱 생성
3. 저장소 연결 및 메인 파일 경로 설정: `Question3.py`

## 파일 구조

```
Question3_streamlit/
├── Question3.py          # 메인 Streamlit 앱
├── requirements.txt       # Python 패키지 의존성
├── .streamlit/
│   └── config.toml       # Streamlit 설정
├── data/
│   └── sunspots.csv      # 태양흑점 데이터
└── README.md             # 프로젝트 설명
```

