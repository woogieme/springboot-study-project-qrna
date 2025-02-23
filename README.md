# QRna
QR 체크인을 이용한 매장의 혼잡도 제공 서비스

## 👨‍👧‍👦 Team Minions

### 백엔드

🧑🏻‍💻 [정재욱](https://github.com/malpipapi)

👨🏻‍💻 [이동현](https://github.com/DongLee99)

👩🏻‍💻 [어정윤](https://github.com/jeongyuneo)

### 프론트엔드

👨🏻‍💻 [임가람](https://github.com/garam918)

👨🏻‍💻 [이명직](https://github.com/LeeMyungJic)

## 🤔 Why?

다들 한번쯤은 코로나가 두려워 사람이 많은 매장, 지역을 피해다닌적이 있을것이다. 나 또한 그랬다. 일일 확진자가 1~2000명을 육박하는 지금 일반인들이 할 수 있는 가장 기초적인 방역 수단은 사람 많은 곳을 피해 다니고 마스크를 잘 착용하는 것이다. 하지만 사람들이 지금 어느 매장이 얼마나 붐비는지 알기 위해서는 직접 가서 확인해 보는 방법 밖에 없다.

포스트 코로나 시대에는 언택트 문화는 지속될 것이라는 전문가들의 전망이 나오고 있으며 새로운 전염병을 대비해 대책을 세우기 위해 방문 기록은 다양한 형태로 발전할 것이라고 예상한다. 또한 코로나로 인해 인파가 많은 곳을 방문하는 것을 기피하는 사람들이 늘어났으나 현재는 매장들에 대한 혼잡도를 제공해주는 서비스가 대중화 되어 있지 않다. 이에 현재 방문 기록을 작성하는 QR코드 인증 방식이 그저 방문 기록만을 목적으로 사용하는 것이 아닌 이를 이용해 다양한 서비스를 개발할 수 있겠다는 생각이 들었다.

QR 인증을 통해 매장 방문기록을 남기는 것은 현재 매장을 사용 중이라는 것을 의미한다. QR 인증을 카운트 값으로 가져 오면 해당 매장의 혼잡도를 파악하는 서비스를 개발할 수 있다. 사용자는 이 서비스를 통해 가고자 하는 매장의 혼잡도를 파악하여 방문할 매장 선택에 도움을 받을 수 있다.

## 😪 What?

주요 **기능**

1. 메인
    - 혼잡 정도를 확인하고자 하는 매장 검색
2. 로그인
    - 간편 로그인(카카오톡, 네이버)
3. 방문 기록
    - QR 인증(이름, 전화번호, 주소)
4. 매장 정보
    - 상호
    - 전화번호
    - 주소
    - 혼잡도(원활/보통/혼잡)

추가 기능

1. 전일/금일 확진자 수 정보 제공
2. 사용자 위치의 거리두기 단계 정보 제공

## ‼️ Problem

- ~~매장별 입장시간을 기준으로 퇴장을 몇 분으로 잡을 것인가?~~
  → 테이블 주문 완료 시 테이블 사용 상태를 미사용 표기

- ~~혼잡의 기준~~
  → 매장 총 수용 가능 인원과 테이블 사람 수를 카운트해서 비율을 정해 혼잡도를 표기# springboot-study-project-qrna