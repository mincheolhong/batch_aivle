# batch_aivle
aivle_school 시작 시 필요한 프로그램들을 한번에 실행시키는 배치 프로그램 입니다.

# config.json 필드 설명
  execute_teams : teams 실행 여부 // 사용시 "True" . 사용X "True" 가 아닌 문자열, 공백 가능<br/>
  teams_path : teams 프로그램 실행파일의 절대 경로 입니다<br/>
  teams_file_name : 확장자를 포함한 teams 파일의 이름입니다.<br/>
  <br/>
  execute_jupyter : jupyter 실행 여부 // 사용시 "True" . 사용X "True" 가 아닌 문자열, 공백 가능<br/>
  jupyter_path : "" // 주피터 실행 파일이 배치 파일과 같아 해당 필드는 사용하지 않습니다.<br/>
  jpuyter_file_name : 주피터 실행 파일이 배치 파일과 같아 파일 속성의 대상에 해당하는 값을 복사해서 입력해 주시면 됩니다.<br/>
  <br/>
  execute_vs : visual_code 실행 여부 // 사용시 "True" . 사용X "True" 가 아닌 문자열, 공백 가능<br/>
  vs_path : vs 프로그램 실행파일의 절대 경로 입니다<br/>
  vs_file_name : 확장자를 포함한 vs 파일의 이름입니다.<br/>
  <br/>
  execute_aivle : aivle_edu 자동 로그인 프로세스 사용 여부 입니다. // 사용시 "True" . 사용X "True" 가 아닌 문자열, 공백 가능<br/>
  id : aivle_edu 아이디 입니다.<br/>
  pw : aivle_edu 비밀번호 입니다.<br/>
  chrome_path : 크롬 실행파일의 절대 경로 입니다.<br/>
  chromedriver_path : 크롬 드라이브의 절대 경로 입니다.<br/>
  run_cmd : 크롬을 원격 디버깅 모드로 실행하기위한 명령어 입니다.<br/>
  url_aivle : aivle_edu url 입니다.<br/>
  id_path : aivle_edu 아이디 입력창 css_selector 경로 입니다.<br/>
  pw_path : aivle_edu 비밀번호 입력창 css_selector 경로 입니다.<br/>
  btn_path : aivle_edu 확인 버튼 css_selector 경로 입니다.<br/>
  otp_path : 인증번호 alet 창의 확인 버튼 css_selector 경로 입니다.<br/>
