# 랜딩페이지 홈페이지 제작
HTML5 시멘틱 태그, CSS변수, 반응형 등 웹 표준과 유지보수성을 고려해서 제작한 일만시간의 법칙 홈페이지입니다.

## 1. HTML5의 시멘틱 태그를 사용하여 구조적으로 마크업을 구현했습니다.
```HTML
 <header>
        <img src="./imges/logo.png" class="header-logo" alt="Hodu">
        <div class="header-text">
            <a href="">Home</a>
            <a href="">About</a>
            <a href="">Support</a>
            <button>Download</button>
        </div>
        <a class="menu" href=""><img src="./imges/menu.svg" alt="메뉴창아이콘"></a>
    </header>
    <div class="wrap">
    <section>
        <h2 class="sc-only">뭔가 다운로드 할 수 있는 히어로 섹션</h2>
        <div class="hero-textbox">
            <h3>Lorem Ipsum is simply
            dummy text of the printing and</h3>
            <p>Lorem Ipsum is simply dummy text of the printing and
                typesetting industry. 
                Lorem Ipsum has been the industry's standard dummy text
                ever since the 1500s, when an unknown</p>
            <button>Download</button>
        </div>
        <img src="./imges/box-cat.png" alt="">
    </section>
```

## 2. CSS 변수(:root)를 통한 컬러시스템 구성
```CSS
:root{
    --main-color:#F2E9D8;
    --sub-color:#D97652;
    --box-color:#263140;
}
```

## 3. 웹 접근성을 고려한 HTML, CSS
sr-only 클래스명을 이용하여 HTML에 있어서 스크린 리더기에 인식은 되지만 보이지 않게 만들었습니다.
```CSS
.sc-only{
    position: absolute;
    left: 9999px;
}
```

## 4. 다양한 디바이스와의 호환을 위한 반응형 구현
```CSS
@media(min-width:768px)

@media (max-width:767px)
```
## 5. 웹 표준 준수
<p align="center">
<img width="70%" alt="웹표준 검사결과" src="https://github.com/rrrr1133/landingpage/issues/1#issue-3742586970">
</p>
