<h3>JSkakaobot</h3><br>
이 앱은 상업적인 목적으로 만든 앱이 아닙니다.<br>
<h4>[1.0]<h4><br>
깃허브 업로드<br>
<h4>[1.12]<h4><br>
4.3~5.0 사이도 지원<br>
호환성 문제 해결<br>
권한 문제 수정<br>
<h3>사용필수조건</h3><br>
-Android Wear 라는 앱이 필요합니다. (플레이스토어에서 다운로드 가능)<br>
-앱설치시 퍼미션권한,알림권한 활성화가 필요합니다.(Android Wear,JSkakaobot 둘다)<br>
-원하는 카카오톡 채팅방 알람 활성화가 필요합니다.(보고 있으면 안됩니다.)<br>
-온/오프 에서 온으로 활성화 시켜야 합니다.<br>
-안드로이드 소프트웨어 버전 18(4.3)이상만 가능합니다. (노피티케이션리스너서비스가 18 부터 있습니다.)<br>
<br>
<h3>사용방법</h3><br>
1.권한 설정하러 가기 버튼 클릭 후 Android Wear,JSkakobot 권한을 허용해줍니다.<br>
2.온/오프에서 온으로 바꿔 활성화 시킵니다.<br>
3.원하는 카톡방의 알람을 활성화 시킵니다.<br>
4.스크립트 편집을 합니다. (스크립트는 0/jskbot/respone.js 에 있습니다.)<br>
5.스크립트 편집이 끝나면 저장 후 앱에서 반드시 스크립트 리로드를 해줍니다.<br>
<h3>사용가능 API</h3><br>
-reply(String Value)<br>
-CurrentTime()<br>
-parsing(final String url, final String tag)<br>
-CoinParsing(final String URL)<br>
-CoinParsingAll(final String URL)<br>
각 메서드 별 사용법은 안드로이드 프로젝트 내에 주석처리 되어있으니, 참고 부탁드립니다.<br>
필요한건 직접 만들어서 사용하셔도 됩니다.<br>
<br>
이 안드로이드 프로젝트의 원작자:만동님<br>
1차 재배포자:이주원님(https://github.com/ljuwon321)<br>
2차 재배포자:나(https://github.com/zxc010613)<br>
1차 재배포자 이신 이주원님도 이게 많이 불안정하다는걸 알고있었습니다.<br>
카카오톡 메세지 전송은 웨어러블API를 이용했다고 합니다.<br>
가장 큰 문제인 방의 이름,그룹채팅방여부를 가져오지 못해 제가 직접 수정하였습니다<br>


