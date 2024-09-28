auto_trading_project/
│
├── config/ # API 키, 설정 파일 등
│ └── settings.py # 설정 관련 파일
│
├── data/ # 수집한 데이터 저장
│ └── selected_coins.csv # 조건에 맞는 종목들
│
├── logs/ # 로그 파일
│ └── trading.log # 거래 내역 및 에러 로그
│
├── src/ # 메인 코드
│ ├── api.py # 빗썸 API와 통신하는 코드
│ ├── strategy.py # 매매 전략 관련 코드
│ ├── trade.py # 매매 실행 코드
│ └── main.py # 프로그램 실행 진입점
│
├── tests/ # 테스트 코드
│ └── test_strategy.py # 전략 테스트
│
├── .gitignore # Git에 올리지 않을 파일들 설정
└── README.md # 프로젝트 설명
