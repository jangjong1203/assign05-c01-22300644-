Deployment

    Vercel 배포 URL
    
Key Learning

    이번 주에 배운 핵심 내용 3가지

CRUD Service

    구현한 서비스 주제
    영화

    사용하는 데이터 Field
    movienumber,title,director,genre,year,rating

    Create: 추가(add) 버튼 클릭시 각 입력창에 데이터가 맞게 입력됬는지 확인후 제대로 입력 되었다면 입력 된 값을 가져와서 배열에 맞게 변환후 배열에 push.

    Read: 배열에 들어있는 값을 각각<td> 형식으로 저장 저장된값을 <tr>의 자식으로 추가해서 화면에 있는 표에 보이게한후 내용이 추가되어도 기존내용이 중복되지않게 불러온 값들을 비어있는값으로 초기화 forEach를 이용해 배열끝까지 반복. 

    Update: 수정 버튼을 추가후 수정버튼을 누른걸 확인하는 변수를 추가. 수정을 누르면 추가 버튼을 저장 버튼으로 변경, 입력창에 수정을 누른 배열의 내용이 뜨도록하고 뜬 내용을 고치고 저장을 누르면 변경된 내용대로 배열에 수정되어 저장. 저장버튼도 다시 추가 버튼으로 변경.
     
    Delete: 삭제 버튼을 누르면 삭제확인 메세지가 뜨고 거기서도 '네'(true)를 누르면 배열에 있는 변수의 id들과 현재 삭제버튼을 누른 변수의id를 비교해서 삭제를 누른 배열의 위치를 확인후 위치를 이용해 배열에서 삭제.
    

    비어있는지 확인, rating이 0점이상 10이하 인지 확인+숫자 확인, 개봉연도 숫자인지 확인. 

JavaScript

    이번 과제에서 사용한 주요 JavaScript 기능을 설명합니다.
    consloe.log: 웹페이지 활동 학인
    querySelector():위에거 하나 가져오기
    addEventListener():이벤트발동시
    createElement():만들기
    appendChild()
    Array:배열
    render()
    splice
    findIndex
    isNaN
AI / Search Usage

    사용한 AI 또는 검색 도구
    어떤 문제를 해결하기 위해 사용했는지
    삭제할 array의 위치를 찾는방법, 수정후 삭제를 누르면 저장버튼을 눌러야 정상적으로 추가버튼으로 돌아옴
    실제 코드에 어떻게 적용했는지
    새롭게 이해한 내용

Problem & Solution

    구현 중 발생한 문제와 해결 방법
    오타: 집중해서 치고 잘 확인하기
Reflection

    이번 과제를 통해 새롭게 알게 된 점 또는 궁금한 점
    자바스크립트 배열