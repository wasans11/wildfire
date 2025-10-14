데이터 설명 

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 114969 entries, 0 to 114968
Data columns (total 15 columns):
 #   Column          Non-Null Count   Dtype   
---  ------          --------------   -----   
 0   Location        114969 non-null  category 위치
 1   Temp (°C)       114957 non-null  float64 기온
 2   WindSpd (m/s)   114901 non-null  float64 풍속
 3   RH (%)          114861 non-null  float64 상대습도
 4   VaporP (hPa)    114907 non-null  float64 수증기압
 5   DewPt (°C)      114874 non-null  float64 이슬점온도
 6   Pressure (hPa)  114872 non-null  float64 기압
 7   GroundT (°C)    114892 non-null  float64 지면온도
 8   Rain(mm)        114969 non-null  float64 강수량
 9   CumRain(24h)    114969 non-null  float64 누적강수량
 10  WinDir          114969 non-null  category 풍향
 11  Wildfire(0/1)   114969 non-null  int64 산불여부
 12  Month           114969 non-null  category 월 
 13  Day             114969 non-null  category 일
 14  Hour            114969 non-null  category 시
