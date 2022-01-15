### 키입력 체크 홈페이지: https://keyboardchecker.com

### 1. 키맵핑 방법
1. 카라비너 설치: https://karabiner-elements.pqrs.org
2. ~/.config/karabiner/assets/complex_modifications 해당 디렉토리에 json 파일 추가 
> caps_lock.json, exchange.json
3. Karabiner -> Complex modifications -> Rules -> Add rule -> Enable

### 2. right_option -> 한영변환 적용 
1. Karabiner -> Simple modifications -> Target device: HHKB-Hybrid_1(PFU Limited) -> right_option : f19
2. 시스템 환경설정 -> 키보드 -> 입력 소스 -> 입력 메뉴에서 다음 소스 선택 F19 (input right_option)

### 3. 해피해킹 키보드 메뉴얼
※ -> 표시는 다음 단계를 의미 합니다.
※ # 표시는 0, 1, 2, 3, 4 단일 숫자를 의미 합니다.
※ + 표시는 순서대로 같이 눌러야 한다는 의미 입니다.

1. 블루투스 등록 : Fn + Q(페어링모드) -> Fn + Ctrl + #1~4 
2. 블루투스 삭제 : Fn + Q(페어링모드) -> Fn + Ctrl + Del + #1~4
> 여기에서 삭제는 키보드 롬에 등록된 블루투스를 삭제하는 것입니다.
3. 등록된 블루투스 모두 삭제 : Fn + Q(페어링모드)-> Fn + Z + Del

4. 블루투스 전환 : Fn + Ctrl + #1~4
> 전환은 #1~4번 등록된 블루투스를 왔다 갔다 할때 사용하는 것입니다.

5. USB 유선연결 전환 : Fn + Ctrl + #0
> 소프트웨어를 사용하려면 USB 연결을 해야 합니다.

6. 페어링모드(Fn + Q) 취소 : Fn + X
7. 윈도우 모드 전환 : Fn + Ctrl + W
8. Mac 모드 전환 : Fn + Ctrl + M

예시
> 윈도우에서 최초 등록을 하려면?
윈도우->설정->장치->Bluetooth 또는 기타 장치 추가->Bluetooth(마우스. 키보드, 팬....)클릭
해피해킹 전원을 키고 Fn+Q 로 페어링 모드로 진입-> Fn+Ctrl+1~4 숫자중 등록하고 싶은 숫자
이렇게 하면 윈도우 화면에 HHKB_Hybrid_1 뭐 이런 식으로 해피해킹 이름이 뜨고 뒤에 등록숫자가 뜹니다.
