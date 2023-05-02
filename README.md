## 참고 사이트 


[visual studio code](https://code.visualstudio.com/)
    
    : 윈도우 환경에서 코드를 쉽게 치기위한 툴
    

--> 설치 후 beautify, live sever 추가로 설치하기.


웹 스탠다드 참고
w3school : https://www.w3schools.com/

웹 관련 서적 참고
(주)도서출판 길벗에서 제공하는 IT 도서 열람 서비스​
thebook : https://thebook.io/

1분코딩
flex  : https://studiomeal.com/archives/197
grid  : https://studiomeal.com/archives/533

netlify : 1000명 이하 무료 개인 사이트 배포 가능
https://www.netlify.com/

codepen : HTML CSS JS 등 연습 및 포트폴리오 업로드 및 가능
https://codepen.io/

figma : 웹 앱 디자인 협업 등 용도로 사용
https://www.figma.com/

배경제거
https://www.remove.bg/ko​

엔티티코드(HTML 상에서 특수기호를 넣고자 할때)
entity code : https://entitycode.com/

폰트어썸(icon 찾아서 넣고자 할때)
fontawesome : https://fontawesome.com/

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/
font-awesome/5.9.0/css/all.min.css" />​

jQuery

jquery 1.x
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>​

깃헙 ----------------------
github : https://github.com/
 - 깃(컴퓨터에 설치하고자 할때)
  git :  https://git-scm.com/downloads

깃 README 등 메모시 사용법
https://m.blog.naver.com/jooeun0502/221956294941​

--------------------------

추가 코드 플러그인

slick
https://kenwheeler.github.io/slick/
cdn

css
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick-theme.min.css"/>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css"/>​

js
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>

jquery 1.x
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>

<!--slick_script-->
 <script>
   $(document).ready(function () {
     $('.slider_pic').slick({
       infinite: false,
       slidesToShow: 1.2,
       dots: true,
       arrows: false,
     });
   });
 </script>

---------------------------

swiper
https://swiperjs.com/

css
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/
swiper@9/swiper-bundle.min.css" />

  <script src="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.js"></script>

  <script>
    const swiper = new Swiper('.shop_product', {
      loop: false,
      slidesPerView: 2.5, //화면에 몇개가 나오게 할것인가?
      spaceBetween: 25, //사이에 간격을 말함.
    });
  </script>

---------------------------------------

light gallery(이미지갤러리 제작시)
https://www.lightgalleryjs.com/

css
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.1/css/lightgallery.min.css" />

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.1/css/lg-thumbnail.min.css" />​

script
  <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.1/lightgallery.min.js"></script>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.1/plugins/thumbnail/lg-thumbnail.min.js">
  </script>
<script>
// light gallery

lightGallery(document.getElementById('lightgallery'), {
  plugins: [lgThumbnail],
});
 </script>

