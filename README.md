# 🚀 Day-Trader-Skills-Suite (미국 주식 · 한국 주식 · 바이낸스 선물 3대 통합 스킬 팩)

인스타그램 릴스(`DfCWYveObmG`)에서 화제가 된 **매수 직전 1만 번 타임머신 시뮬레이터(`trader-timemachine`)**, **전 종목 돌파 차트 스캐너(`trader-scanner`)**, **미국 국회의원 거래 추적기(`trader-pelosi`)** 등 전체 오픈소스 스킬 3종 세트를 한곳에 통합한 저장소입니다.

---

## 📂 폴더 구성 (3대 시장 전수 수록)

### 1. [`1_US_Trader_Skill_11`](./1_US_Trader_Skill_11) (미국 주식 원본 11종 스킬)
- `trader-screener` : 미국 주식 전 종목 차트/수급 필터 스캐너
- `trader-pelosi` : 낸시 펠로시 등 미국 상·하원 국회의원 주식 매매 공시 추적기
- `trader-copycat` : SEC 13F 공시 기반 월가 기관/거물 포트폴리오 복제 추적
- `trader-analyst` : SEC 실적 공시(매출, EPS, 마진) 자동 분석
- `trader-news` : 속보 헤드라인 및 SEC 8-K 공시 실시간 감시
- `trader-risk` / `trader-budget` / `trader-rebalance` / `trader-tax` / `trader-alerts` / `trader-broker`

### 2. [`2_KR_Stock_DayTrader_Skill`](./2_KR_Stock_DayTrader_Skill) (국내 주식 단타 전용 9종 스킬)
- **`trader-kr-timemachine`** : 국내 주식 매수 직전 10,000회 몬테카를로 시뮬레이션으로 익절 확률 vs 손절 확률('동전 던지기' 여부) 사전 판독
- **`trader-kr-scanner`** : 국내 주식 실시간 급등/돌파 종목 스캐너
- `trader-kr-entry` / `trader-kr-exit` : 국내 주식 진입 타점 및 분할 청산 전략
- `trader-kr-risk` / `trader-kr-budget` : 1회당 손실 제한 및 예수금 비중 관리
- `trader-kr-journal` / `trader-kr-lab` / `trader-kr-today` : 매매 복기 일지 및 백테스트 연구소

### 3. [`3_Crypto_Futures_DayTrader_Skill`](./3_Crypto_Futures_DayTrader_Skill) (바이낸스 선물 단타 전용 10종 스킬)
- **`trader-timemachine`** : 바이낸스 선물 포지션 진입 전 10,000번 궤적 시뮬레이션
- **`trader-funding`** : 바이낸스 선물 펀딩비 과열 및 롱/숏 스퀴즈 역추세 포착
- **`trader-scanner`** : 바이낸스 선물 거래대금 및 변동성 돌파 코인 스캐너
- `trader-entry` / `trader-exit` / `trader-risk` / `trader-budget` / `trader-news` / `trader-alerts` / `trader-broker`
