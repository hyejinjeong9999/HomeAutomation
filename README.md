2020-05-01

- git branch 생성; kwon 내꺼, dev 개발브랜치, origin 건들지마
- push denied; 기존 사용자 'csy****' 계정으로 계속 접속됨.
	- (1) Credential Manager(자격 증명 관리자) -> Windows 자격 증명 -> github이랑 SSO 삭제
	- (2) $git credential-manager uninstall -> ID/PW 재입력
- round_button, 토글버튼3개 구현.
	- 기능구현 아직
	- 아이콘 아직



2020-05-06

- 너무 피곤
- 메인 UI, 창문 UI 
- 자동/수동 기능
	수동은 알람 형식으로



2020-05-07

- ON/OFF ImageButton 구현
	selector 2개(imagebtn_selector, imagebtn_icon_selector)
- 현제 온도 TextView 구현
	id/fragACurrentTemp


2020-05-08

- ImageButton 변경
	ON/OFF > OPEN/CLOSE
- WeatherVO > setWeather 에서 icon 
- setOnCheckedChangeListener > 에어컨 on/off Toast메세지 띄울것.
- SystemInfoWeather > 값 설정할것.
- bundleFagmentA > 상태창을  recycler_item_weatherinfo 활용
	- recycler_item_weatherinfo 에 VO값 대입



2020-05-09
- 멘토 특강