# GGF Soft

## bootstrap4 jquery d3 

#### 스크립트 도입부에 변수들만 세팅하면 그래프가 문제없이 표현 되도록 하드코딩 배제
#### 바로 카피해서 쓸 수 있도록 템플릿화 했음
#### target --> myGraph 가 반드시 존재 

### defaultD3 [defaultD3.html](template/defaultBs4.html) 
- jquery, bootstrap, d3 준비 
- bootstrap 기본 화면 
 
 ### horizontal02 [horizontal02.html](template/horizontal/horizontal02.html) 
 - jquery, bootstrap, d3 준비 
 - bootstrap Layout d3 세로 막대 그리기
 - **<u>d3에서의 x, y는 DIV 영역 안에 포지션을 상속</u>**

 ### horizontal03 [horizontal03.html](template/horizontal/horizontal03.html) 
 - jquery, bootstrap, d3 준비 
 - bootstrap Layout d3 세로 막대 그리기
 - **<u>target svg 에 대한 width, height 설정</u>**
 - apply css to graph

 ### horizontal04 [horizontal04.html](template/horizontal/horizontal04.html) 
 - include horizontal03 function
 - add the function which animate graph

 ### horizontal05 [horizontal05.html](template/horizontal/horizontal05.html) 
 - include horizontal04 function
 - add the function which click action 

 ### hAxis01 [hAxis01.html](template/horizontal/axis/hAxis01.html) 
 - include horizontal05 function
 - add horizontal axis **<u>this is not static code ( ratio calculate )</u>**

 ### hAxis02 [hAxis02.html](template/horizontal/axis/hAxis02.html) 
 - include hAxis01 function
 - dataSet add, delete, update **<u>this is not static code ( ratio calculate )</u>**
 - add custom area 
 
### circle01 [circle01.html](template/circle/circle01.html) 
  - jquery, bootstrap, d3 ready
  - circle graph base
  
### circle02 [circle02.html](template/circle/circle02.html) 
  - include circle01 function
  - add color graph
  
### circle03 [circle03.html](template/circle/circle03.html) 
  - include circle02 function
  - add text
  
### circle04 [circle04.html](template/circle/circle04.html) 
  - include circle03 function
  - add value text
  - add mouseover action
  
### vertical [vertical01.html](template/vertical/vertical01.html) 
  - include [defaultD3.html](template/defaultD3.html)
  - add vertical graph 
  - add text to bar

### line [line01.html](template/line/line01.html) 
  - include [defaultD3.html](template/defaultD3.html)
  - line chart
   
### line [line02.html](template/line/line02.html) 
  - include line01
  - dynamic y axis
  - scale apply
  
### line [line03.html](template/line/line03.html) 
  - include line02
  - many line

### line [line04.html](template/line/line04.html) 
  - include line03
  - json data mapping 

### line [line05.html](template/line/line05.html) 
  - include line04
  - set x axis
  
### line [line06.html](template/line/line06.html) 
  - include line05
  - horizontal text  x axis  
  
### line [line07.html](template/line/line07.html) 
  - include line06
  - auto set 
  
### table2chart [table2json.html](template/table2chart/table2json.html) 
  - table to json data
  - auto set   
  
### table2chart [table2json2line.html](template/table2chart/table2json2line.html) 
  - include table2json
  - table -> json -> line chart    

### table2chart [table2json2line2.html](template/table2chart/table2json2line2.html) 
  - include table2json2line
  - mouseover -> table selected

![screenshot](https://github.com/parkseungchul/D3_SAMPLE/blob/master/images/002.PNG)  
### table2chart [table2json2line3.html](template/table2chart/table2json2line3.html) 
  - include table2json3line2
  - 선 그래프 그림을 함수화하여 사용
  
  