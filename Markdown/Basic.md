# Mastering Markdown
<!--Heading-->
### *Head Size* : <br>
> #의 갯수에 따라 결정된다.

####  **Code**
```
# H1 Head Size
## H2 Head Size
### H3 Head Size
#### H4 Head Size
##### H5 Head Size
```
#### **Result**
  
# H1 Head Size
## H2 Head Size
### H3 Head Size
#### H4 Head Size
##### H5 Head Size
___
<!--Line-->
### *Line* : <br>
> 언더바('_') 3번 입력한다.

#### **Code**
```
___
```
#### **Result**
___

<!--Text attributes-->
### *Text attributes* : 
>텍스트 좌우로 별(*) 을 한번씩 입력하면 Italic, 두번씩 입력하면 Bold 표시된다. 물결(~)를 두번씩 입력하면 Strikethrough로 표시된다.

#### **Code**
```
*Italic*
**Bold**
~~Strikethrough~~
```
#### **Result**

*Italic*<br>
**Bold**<br>
~~Strikethrough~~<br>

<!--Quote-->
### *Quote* : <br>
부등호(>) 표시하면 분기처리된다.

#### **Code**
```
> Quote
```
#### **Result**
> Quote
<br>
___
<br>

<!--Bullet List-->
### *Bullet List* : <br> 
> 별(*)을 텍스트 앞에 표시하면 Bullet이 생성된다.
#### **Code**
```
Bullet
```
#### **Result**
* Bullet

___
<!--Numbered List-->
### *Numbered List* : 
>숫자 입력하면 자동 엔터되어 리스트 형태가 완성된다.
```
1. Number1
2. Number2
3. Number3
```
#### **Result**
1. Number1
2. Number2
3. Number3

<!--Link-->
### *Link*<br>
> 링크할 단어 좌우에 대괄호'[]'를 표시하고 링크해야할 사이트를 ']' 뒤에 괄호'()' 안에 링크주소를 입력한다.

#### **Code**
```
naver.com [Here](http://www.naver.com)
```
#### **Result**
naver.com [Here](http://www.naver.com)

<!--Image-->
### *Image*<br>
> 

#### **Code**
```
![Image description](https://cdn.pixabay.com/photo/2017/05/24/06/53/dep-2339693_1280.jpg)
```
#### **Result**
![Image description](https://cdn.pixabay.com/photo/2017/05/24/06/53/dep-2339693_1280.jpg)

<br>

<!--Table-->
### *Table*
> | 로 구분해서 열을 정하고 --로 행을 정한다.
정렬의 경우는 행을 정한 --를 기준으로 왼쪽 오른쪽 표기하면 된다.

#### **Code**
```
기본
|Table|Column|
|--|--|
|TableA|Column1|
|TableA|Column2|

왼쪽정렬
|Table|Column|
|:--|:--|
|TableA|Column1|
|TableA|Column2|

오른쪽정렬
|Table|Column|
|--:|--:|
|TableA|Column1|
|TableA|Column2|

가운데정렬
|Table|Column|
|:--:|:--:|
|TableA|Column1|
|TableA|Column2|
```
#### **Result**
기본
|Table|Column|
|:--|:--|
|TableA|Column1|
|TableA|Column2|

오른쪽정렬
|Table|Column|
|--:|--:|
|TableA|Column1|
|TableA|Column2|

가운데정렬
|Table|Column|
|:--:|:--:|
|TableA|Column1|
|TableA|Column2|

___
<!--Code-->
### *Code*
> Inline Code는 백틱키(`) 한번씩 로 텍스트를 감싸고, Code Bluck 백틱키(`) 세번씩 텍스트를 감싸면 된다.

#### **Code**
```
Code `console.log('your message')`
Code ```

     end```
```
####
Code `console.log('your message')`