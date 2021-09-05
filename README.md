# Knowre 웹개발 커리큘럼 - 4th Edition, 2021

## 소개
* Knowre의 신입 웹 개발자 교육을 위한 웹 개발 교육 커리큘럼의 2021년 버전입니다.
* 이 커리큘럼을 통해 신입 개발자들은 git, HTML, CSS, front-end JavaScript, node.js, MySQL, 그리고 더 나아가 선택된 몇 가지의 최신 웹 기술과 그 작동 원리에 대해 익히게 됩니다.


## 머리말

* [머리말](./PREFACE.md)


## 목차

<details><summary>펼치기</summary>
  <p>

  * [Quest 00. 형상관리 시스템](./Quest00)
  * [Quest 01. HTML과 웹의 기초](./Quest01)
  * [Quest 02. CSS의 기초와 응용](./Quest02)
  * [Quest 03. 자바스크립트와 DOM](./Quest03)
  * [Quest 04. OOP의 기본](./Quest04)
  * [Quest 05. OOP 특훈](./Quest05)
  * [Quest 06. 인터넷의 이해](./Quest06)
  * [Quest 07. node.js의 기초](./Quest07)
  * [Quest 08. 웹 API의 기초: REST와 CRUD](./Quest08)
  * [Quest 09. 서버와 클라이언트의 대화](./Quest09)
  * [Quest 10. 인증의 이해](./Quest10)
  * [Quest 11. RDB의 기초와 ORM](./Quest11)
  * [Quest 12. 보안의 기초](./Quest12)
  * [Quest 13. 웹 API의 응용과 GraphQL](./Quest13)
  * [Quest 14. 정적 분석: 타입스크립트와 린트 시스템](./Quest14)
  * [Quest 15. 자동화된 테스트](./Quest15)
  * 프론트엔드 루트
    * [Quest 16-F. 컴포넌트 기반 개발](./Quest16-F)
    * [Quest 17-F. 번들링과 빌드 시스템](./Quest17-F)
    * [Quest 18-F. 프로그레시브 웹앱](./Quest18-F)
    * [Quest 19-F. 웹 어셈블리의 기초](./Quest19-F)
  * 백엔드 루트
    * [Quest 16-B. 도커와 컨테이너](./Quest16-B)
    * [Quest 17-B. 배포 파이프라인](./Quest17-B)
    * [Quest 18-B. 서비스의 운영: 로깅과 모니터링](./Quest18-B)
    * [Quest 19-B. 서버 아키텍쳐 패턴](./Quest19-B)
  * [Quest 20. 세상 밖으로](./Quest20)

  </p>
</details>


## 커리큘럼을 진행하실 때...

* 커리큘럼을 수행하시다 보면 이미 익숙한 주제도 있을 수 있고, 익숙하지 않은 주제도 있을 것입니다. 퀘스트가 익숙한 주제를 다루고 있더라도 본인이 정확히 알지 못하고 있는 부분이 분명히 있을 것입니다.
* Checklist의 질문들을 무시하지 마십시오! 본인이 좋은 개발자로 성장하기 위한 밑거름이 될 수 있고, 본격적으로 바쁜 업무를 시작한 이후에는 이 밑거름을 잘 채우는 것은 생각보다 어려운 일입니다.
* 되도록 여러 개의 퀘스트를 동시에 진행하지 않는 것을 권장합니다. 진도를 빠르게 나가는 것도 중요하지만, 한 개의 주제를 깊고 정확히 아는 것이 더 중요합니다. 여건이 닿는 한 번에 한 개의 퀘스트씩만 수행하고, 완성한 다음에 꼭 바로 피드백을 받아 놓친 부분이 무엇인지 점검하도록 합시다.
* 생소한 주제의 퀘스트를 수행하는 경우, 본인이 새로운 개념을 공부해 나가는 방식을 정립하는 기회로 생각하시면 좋습니다. 그런 공부의 과정은 앞으로 개발자의 커리어를 걸어가는 동안 계속해서 겪게 될 것입니다!
* 이 커리큘럼에서 다루는 기술 뿐 아니라 모든 기술은 어떤 특정한 문제를 풀기 위해 개발되었습니다. 커리큘럼을 진행하시면서, 또 이후에 개발자의 길을 걸을 때 언제나 다음의 세 가지 질문을 끊임없이 스스로에게 던지면 유용할 것입니다:
  * 이 기술이 왜 나오게 되었을까? 어떤 문제를 풀기 위해 어떤 배경에서 나왔을까?
  * 이 기술은 기존의 문제를 푸는 해답을 어떻게 제시했을까? 이 기술은 어떻게 사용하는 것일까?
  * 이 기술은 어떤 장점과 단점을 가지고 있을까? 이 기술의 단점을 보완하려면 어떻게 해야 할까? 기존의 문제를 푸는 다른 방법으로 제시된 것은 무엇이 있을까?


## 설명

* Quest 0부터 순서대로 각각의 주제들에 관한 퀘스트를 수행하시면 됩니다.
* Quest 0에서 이야기하고 있는 바와 같이, 이 repo를 fork하여 자신의 저장소를 만들고, 그 저장소에서 퀘스트 수행이 이루어질 예정입니다.
* 비밀번호나 토큰 스트링 등의 민감한 정보를 공개된 저장소에 커밋하지 않도록 주의하시기 바랍니다.
* 퀘스트는 다음과 같이 구성되어 있습니다(그러나 모든 퀘스트가 다음의 구성요소들을 모두 가지고 있는 것은 아닙니다).
  * Introduction: 소개 페이지입니다.
  * Topics: 이번 퀘스트를 통해 익힐 수 있는 기술이 무엇인지를 나타냅니다.
  * Resources: 토픽을 익히기 위해 참고하면 좋을 링크들입니다.
  * Checklist: Topic들을 제대로 공부했는지를 자문자답 할 수 있는 문항들로 이루어져 있습니다.
  * Quest: 퀘스트를 통해 만들어내야 하는 결과물들을 담고 있습니다.
  * Skeleton: 퀘스트 수행을 위한 스켈레톤 코드입니다.
  * Advanced: 더 공부하고 싶은 분들을 위한 화두입니다.


## 제출

* 퀘스트의 제출은 자신의 저장소에 Push하는 것으로 이루어 집니다. 가급적 자주 커밋하고 자주 푸시하는 것을 권장합니다.
* Checklist의 질문에 대한 대답은 이 저장소를 fork하여 자신의 저장소를 만들고, 그 저장소에 해당 내용을 푸시합니다.
  * Checklist의 대답은 마치 면접 질문에 대답하듯 최대한 정확하지만 간결한 답을 준비하는 것이 좋습니다.
    * 혹시 답변에 있어 포맷팅이 필요할 경우 [Markdown 포맷](https://guides.github.com/features/mastering-markdown/)을 이용하시는 것을 권장해 드립니다.
      * 이 커리큘럼의 많은 문서들도 Markdown으로 되어 있기 때문에 Markdown 포맷에 익숙해지시는 것 역시 권장드립니다.
    * Checklist의 내용을 채워넣기 위해 구글링해서 나온 결과물을 그대로 붙여넣기보다는, 본인이 내용을 이해한 후 되도록 면접장에서 대답한다는 마음가짐으로 자신의 언어로 다시 작성하기를 권장합니다.
* Quest의 결과물은 대부분의 경우 skeleton 파일의 TODO 부분을 채워넣는 것으로 충분합니다.
  * 충분히 익숙해진 후반부에는 Skeleton 코드를 굳이 제공하지 않습니다.
* 각각의 퀘스트들은 초반부터 후반까지, 앞에서 했던 퀘스트의 결과물에 살을 붙이는 식으로 매우 긴밀히 연결되어 있습니다.
  * 그렇기 때문에 중간에 한 퀘스트를 건너뛰면 이후의 퀘스트들의 진행에 어려움이 있을 수 있습니다.
* Checklist와 Quest의 질문과 답을 완벽히 이해했다고 생각하신다면, Advanced에 있는 화두를 스스로 공부해 보고 필요한 경우 질문거리를 생각해 봅니다.


## 막혔다면...

* 되도록 검색 등을 통해 스스로 해결해 나가는 것을 권장합니다. 국내 검색엔진의 검색 보다는 구글 검색을 권장합니다.
* 어떠한 알 수 없는 현상이 있어 막혔을 경우 그 현상이 일어나는 최소단위의 코드를 만들다 보면 해결되는 경우가 많습니다.
* 만일 만 하루 이상의 시행착오로 인해 진행이 멈췄을 경우, 제 자리로 찾아 오시면 해결을 보장해 드립니다.


### 라이센스

* 이 커리큘럼은 [MIT 라이센스](./LICENSE)를 따릅니다. 원하시는대로 쓰시고 개작하실 수 있습니다. 다만 이 커리큘럼의 내용이 마음에 드셨을 경우, 만약 원하신다면 `[Knowre Web Development Curriculum](https://github.com/Knowre-Dev/WebDevCurriculum)에서 영감을 받았다` 라는 언급을 해 주시면 감사하겠습니다.
