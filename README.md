# 1주차

## 1. HTML, CSS 기본 내용
- HTML과 CSS의 개념
  - HTML은 뼈대, CSS는 꾸미기
  
    ```
    HTML은 구역과 텍스트를 나타내는 코드로, CSS는 잡은 구역을 꾸며주는 것
    HTML 내 style 속성으로 꾸미기를 할 수 있지만, 긴 세월동안 이것을 한데 모아 볼 수 있는 CSS 파일이 있어 
    HTML 코드 내에 CSS 파일을 불러와서 적용한다.
    ```
    
- HTML 기초
  - HTML은 크게 head와 body로 구성되며, head안에는 페이지의 속성 정보를, body안에는 페이지의 내용을 담는다.
- head 안에 들어가는 대표적인 요소들: meta, script, link, title 등

  ```
  페이지의 속성을 정의하거나, 필요한 스크립트들을 부릅니다. 즉, 눈에 안 보이는 필요한 것들을 담는 것.
  ```

- body 안에 들어가는 대표적인 요소들!
  ```
  <!-- 구역을 나누는 태그들 -->
    <div> 구역 </div>
    <p> 문단 </p>
    <ul>
        <li> bullet point!1 </li>
        <li> bullet point!2 </li>
    </ul>
    
    <!-- 구역 내 콘텐츠 태그들 -->
    <h1>h1은 제목 </h1>
    <h2>h2는 소제목 </h2>
    <h3> h3~h6 </h3>
    <hr>
    span 태그: 특정 <span style="color:red"> 글자 </span>를 꾸며줌
    <hr>
    a 태그: <a href="http://naver.com/"> 하이퍼링크 </a>
    <hr>
    img 태그: <img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" />
    <hr>
    input 태그: <input type="text" />
    <hr>
    button 태그: <button> 버튼입니다</button>
    <hr>
    ```
    
 - CSS연습
   - margin과 padding
    ```
    margin은 바깥 여백을, padding은 내 안쪽 여백
    
    만들어둔 이미지를 가운데로 가져오는 경우
    적절한 width와 margin:auto를 사용하자
    ```
 - 부트스트랩
   - 부트스트랩이란? 예쁜 CSS를 미리 모아둔 것
   
 - Javascript 
   - 프로그래밍 언어 중 하나로, 브라우저가 알아들을 수 있는 언어
   
 - Javascript 기초 문법
   - 리스트 & 딕셔너리
   ```
   리스트: 순서를 지켜서 가지고 있는 형태
   
    let a_list = []  // 리스트를 선언. 변수 이름은 역시 아무렇게나 가능!

    // 또는,

    let b_list = [1,2,'hey',3] // 로 선언 가능

    b_list[1] // 2 를 출력
    b_list[2] // 'hey'를 출력

    // 리스트에 요소 넣기
    b_list.push('헤이')
    b_list // [1, 2, "hey", 3, "헤이"] 를 출력

    // 리스트의 길이 구하기
    b_list.length // 5를 출력
    ```
    ```
    딕셔너리: 키(key)-밸류(value) 값의 묶음
    let a_dict = {}  // 딕셔너리 선언. 변수 이름은 역시 아무렇게나 가능!

    // 또는,

    let b_dict = {'name':'Bob','age':21} // 로 선언 가능
    b_dict['name'] // 'Bob'을 출력
    b_dict['age'] // 21을 출력

    b_dict['height'] = 180 // 딕셔너리에 키:밸류 넣기
    b_dict // {name: "Bob", age: 21, height: 180}을 출력
    ```
    ```
    리스트와 딕셔너리의 조합
    names = [{'name':'bob','age':20},{'name':'carry','age':38}]

    // names[0]['name']의 값은? 'bob'
    // names[1]['name']의 값은? 'carry'

    new_name = {'name':'john','age':7}
    names.push(new_name)

    // names의 값은? [{'name':'bob','age':20},{'name':'carry','age':38},{'name':'john','age':7}]
    // names[2]['name']의 값은? 'john'

  - Javascript 기초 문법2
    ```
    조건문
    unction is_adult(age){
      if(age > 20){
        alert('성인이에요')
      } else {
        alert('청소년이에요')
      }
    }

    is_adult(25)
    ================================
    
          function is_adult(age){
        if(age > 20){
          alert('성인이에요')
        } else if (age > 10) {
          alert('청소년이에요')
        } else {
          alert('10살 이하!')
        }
      }

      is_adult(12)
    
    ```
    ```
    반복문
        for (let i = 0; i < 100; i++) {
      console.log(i);
    }
    ```


