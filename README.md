## 📝 LabVIEW_Study <br>


**✨ LabVIEW(Laboratory Virtual Instrument Engineering Workbench)**

**시각적 프로그래밍 환경** - LabVIEW는 그래픽 사용자 인터페이스(GUI)를 제공하여 사용자가 프로그램을 쉽게 작성하고 이해할 수 있도록 도와줌. 이는 복잡한 알고리즘을 시각적으로 구성하여 표현할 수 있음

**다양한 응용 분야** - LabVIEW는 과학, 공학, 의료, 자동화, 제조 및 테스트 시스템 등 다양한 분야에서 사용됨. 실시간 데이터 수집, 장치 제어, 신호 처리, 이미지 분석 등의 다양한 응용 프로그램을 개발하는 데 사용됨

**모듈화 및 재사용성** - LabVIEW는 모듈화된 설계와 재사용 가능한 코드를 촉진함. 이는 개발 시간을 단축하고 프로그램의 유지보수를 쉽게 만들어줌

**실시간 및 임베디드 시스템** - LabVIEW는 실시간 및 임베디드 시스템에서 사용될 수 있음. 실시간 시스템에서 데이터를 실시간으로 처리하고 응용프로그램을 제어할 수 있도록 도와줌

**📌 LabVIEW는 왼쪽 상단에서 오른쪽 하단으로 물이 흘러 내리는 것처럼 프로그램이 실행됨**

## **📄 LabVIEW의 구성요소** <br>
**VI (Virtual Instrument)** - 가상 계측기를 나타내는 기본 단위, 프로그램의 기능과 동작을 정의하는 프로그램 코드가 포함 <br>
**Front Panel** - 사용자 인터페이스(GUI)를 구성하는 곳, 사용자가 입력하거나 시각적으로 확인할 수 있는 요소들이 포함 <br>
**Block Diagram** - VI의 Block Diagram은 LabVIEW 프로그램의 실제 코드를 시각적으로 표현하는 곳, 데이터의 흐름, 연산, 제어 구조 등을 시각적으로 연결하여 프로그램을 작성 <br>
**Controls** - Front Panel에서 사용자의 입력을 받는 요소들을 나타냄 ex) 텍스트 상자, 버튼, 슬라이더 등 <br>
**Indicators** - Front Panel에서 프로그램의 상태나 결과를 표시하는 요소들을 나타냄 ex) 숫자 표시기, 그래프, LED 등 <br>
- 검은색 삼각형 모양이 오른쪽에 있는 것은 사용자의 입력을 받아서 데이터가 출력으로 나간다고 보는 것이기 때문에 **Controls** <br>
- 검은색 삼각형 모양이 왼쪽에 있는 것은 데이터를 받아서 받은 것을 보여주는 것이기 때문에 **Indicators** <br>

**Wires** - Block Diagram에서 데이터의 흐름을 나타내는 선. 데이터가 함수로 전달되거나 연결될 때, 이들을 통해 데이터의 흐름을 확인할 수 있음 <br>


## **🛠 LabVIEW 시작하기**
1. LabVIEW 소프트웨어 설치: 먼저 National Instruments 또는 NI 웹사이트에서 LabVIEW 소프트웨어를 다운로드하고 설치(일반적으로 라이센스를 구입하거나 평가판을 다운로드하여 설치할 수 있음) <br>
**📌LabVIEW 다운로드 사이트 :** https://www.ni.com/ko/support/downloads/software-products/download.labview.html#521715 <br>
2. LabVIEW 실행: LabVIEW를 설치한 후, 컴퓨터에서 LabVIEW 아이콘을 찾아 실행. LabVIEW는 일반적으로 시작 메뉴나 데스크톱에 바로가기로 추가됨 <br>
3. 실행 화면 탐색: LabVIEW를 실행하면 시작 화면이 나타남. 여기서는 새로운 프로젝트를 생성하거나 기존의 프로젝트를 열 수 있음 <br>
4. 새로운 VI(가상 계측기) 생성: LabVIEW에서 VI는 가상 계측기를 나타냄. 새로운 VI를 생성하려면 "File" 메뉴에서 "New VI"를 선택하거나, 시작 화면에서 "Blank VI"를 선택 <br>
5. 프로그래밍 및 디자인: LabVIEW에서 VI를 디자인하고 프로그래밍하는 방법을 익혀야함. LabVIEW는 그래픽 프로그래밍 언어이기 때문에, 프로그램을 작성할 때 마우스로 요소들을 드래그하고 놓아서 연결하고 구성할 수 있음 <br>
6. 실행 및 테스트: VI를 작성한 후에는 실행하여 프로그램이 예상대로 동작하는지 확인. 오류가 발생하거나 수정해야 할 부분이 있으면 다시 수정하고 테스트 <br>

**✨ node.js 설치 이유 : create-react-app 라이브러리 때문**
- node.js 설치하면 npm(Node Package Manager)을 통해 다양한 라이브러리와 모듈을 손쉽게 관리할 수 있음
- npm으로 create-react-app 이용
  
**✨ 데이터 바인딩**
- 변수에 넣기
- state에 넣기
- 이벤트 핸들러를 통한 데이터 바인딩
- Props를 이용한 데이터 바인딩

**✨ state** 
- state(state가 변경되면 HTML이 재렌더링 됨)
1. 변수 대신 쓰는 데이터 저장공간
2. useState()를 이용해 만들어야함 ```[state 데이터, state 데이터 변경 함수]```
- state 사용하기
1. {useState} 상단에 첨부 ```import React, { useState } from 'react';```
2. useState(데이터)
3. 문자, 숫자, array, object 다 저장가능 <br>
```let [글제목, 글제목변경] = useState(['여자 옷 추천', '수원 맛집']);```
{글제목[1]} -> 하면 여자 옷 추천 출력 <br>
<자주 바뀌는, 중요한 데이터를 변수 말고 state로 저장해서 쓰기>
- 데이터 수정 방법
1. 기존 state 카피본 만들기
2. 카피본에 수정사항 반영하기
3. 변경함수()에 집어넣기

**✨ onClick** <br>
```onClick={클릭될 때 실행할 함수}``` <br>
```onClick ={()=>{실행할 내용}}```


## **✨ Component** <br>
- 리액트에서의 Component는 UI를 구성하는 요소로서 독립적이고 재사용 가능한 코드 블록
- 각각의 컴포넌트는 자체적으로 상태(state)와 속성(props)을 가질 수 있으며, 이를 통해 동적이고 유연한 UI를 만들 수 있음
- Component 만드는 법(funtcion App() 끝나는 부분에 작성, function App()도 일종의 Component)
1. 함수 만들고 이름짓고
2. 축약을 원하는 HTML 넣고
3. 원하는 곳에서 <함수명/>
- Component 유의사항
1. 이름은 대괄호
2. return() 안에 있는건 태그하나로 묶어야함
3. 하나의 div 태그로 묶기 싫다면 <>, </>로 묶기
- Component로 묶으면 좋은 것
1. 반복 출현하는 HTML 덩어리들
2. 자주 변경되는 HTML UI들

**✨ Component 타입**
- 함수형 컴포넌트 (Functional Components): ES6의 화살표 함수나 일반 함수를 사용하여 정의되며, 주로 상태나 생명주기 메서드가 필요하지 않은 단순한 컴포넌트에 사용됨

- 클래스형 컴포넌트 (Class Components): ES6의 클래스를 사용하여 정의되며, 상태나 생명주기 메서드 등의 기능을 활용할 수 있음

## **✨ Props(properties의 줄임말)** <br>
-  React 컴포넌트 간에 데이터를 전달하는 메커니즘

```import React from 'react';
부모 컴포넌트
import ChildComponent from './ChildComponent';

function ParentComponent() {
    const name = "John";
    return (
        <ChildComponent name={name} />
    );
}

자식 컴포넌트
import React from 'react';

function ChildComponent(props) {
    return (
        <p>Hello, {props.name}!</p>
    );
}

// 렌더링 결과
<p>Hello, John!</p>


