# Korail Ticket Hunter

코레일 기차 승차권 예매를 도와주는 프로그램입니다.

## 기능
- 출발역/도착역 기반 티켓 검색
- 자동 새로고침 및 알림
- 이메일 알림 지원
- 사용자 친화적인 GUI

## 설치 방법

1. 저장소 클론
```bash
git clone https://github.com/yourusername/korail-ticket-checker.git
cd korail-ticket-checker
```

2. 가상환경 생성 및 활성화
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
```

3. 의존성 설치
```bash
pip install -r requirements.txt
```

4. 환경변수 설정
```bash
cp .env.example .env
# .env 파일을 수정하여 이메일 설정을 입력
```

## 사용 방법

1. 프로그램 실행
```bash
python -m korail_ticket.main
```

2. GUI를 통해 검색 조건 입력
   - 출발역과 도착역 입력
   - 날짜 선택
   - 시간대 선택
   - 검색 간격 설정

3. '검색 시작' 버튼 클릭