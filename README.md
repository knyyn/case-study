/* ======================
      スマホ用スタイル 
 ====================== */

  * {
    box-sizing: border-box;
    margin: 0 0 0 0;
  }

  body {
    margin: 0 0 0 0;
  }

  a:link, a:visited, a:hover, a:active {
    color: #fff9ec;
    text-decoration: none;
  }

 /* 画面幅が600px以下のとき */
 @media screen and (max-width: 600px) {

  /* ヘッダー */

  header {
    position: fixed;
    display: flex;
    justify-content: space-between;
    padding: 0 20px 0 20px;
    width: 100%;
    height: 60px;
    margin: 0 0 0 0;
    z-index: 99;
   }

   .store_logo {
    font-weight: bold;
    color: #fff9ec;
    font-size: 18px;
    position: relative;
    top: 12px;
    text-decoration: none;
    font-family: "Playfair Display",serif;
   }

   /* ハンバーガーメニュー */
   .hamburger_open {
    margin: 30px 0 30px 0;
    width: 30px;
   }

   .ham_cercle {
    position: absolute;
    right: 20px;
    border-radius: 50%;
    background-color: rgba(255, 249, 236, 0.25) ;
    top: 10px;
    align-items: center;
    width: 50px;
    height: 50px;
   }

   .ham_open {
    display: block;
    width: 50%;
    height: 3px;
    z-index: 100;
    margin-top: 3px;
    border-radius: 2px;
    background-color: #fff9ec;
    position: relative;
    left: 12px;
    top: 14px;

  }

  .list_nav_header {
    display: none;
  }

  /* ハンバーガーメニュー　中身 */
  /* #nav_sp {
    background-color: #805320;
    position: fixed;
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    z-index: 100;
  }

  .hamburger_close {
    position: absolute;
    top: 20px;
    right: 20px;
  }

  .hamburger_close .ham_close_1 {
    position: absolute;
    top: 13px;
    left: -50px;
    display: inline-block;
    width: 20px;
    height: 2px;
    content: '';
    transform: rotate(-45deg);
    background-color: #fff9ec;
  }

  .hamburger_close .ham_close_2 {
    position: absolute;
    top: 13px;
    left: -50px;
    display: inline-block;
    width: 20px;
    height: 2px;
    content: '';
    transform: rotate(45deg);
    z-index: 100;
    background-color: #fff9ec;
  }

  .list_nav_header {
    padding-left: 35px;
    padding-right: 35px;
    margin: 0;
  }

  .area_logo_header .store_logo {
    margin: 20px;
    color: #fff9ec;
  }

  .list_nav_header > li {
    display: block;
    font-size: 18px;
    font-weight: bold;
  } */

  /* ハンバーガーメニューの背景画像 */
  /* .ham_img {
    width: 100%;
  }

  .ham_img .ham_img1 {
    max-width: 100%;
  } */

  /* メインビジュアル */

  .main_visual_pic1 {
    width: 100%;
    background-color: #805320;
    /* max-width: 100%; */
  }

  .main_pic {
    /* width: 100%; */
    max-width: 100%;
  }

  .concept_message .message_01 {
    font-family: "YuKyokasho",sans-serif;
    font-size: 25px;
    position: absolute;
    right: 40px;
    top: 65px;
    color: #fff9ec;
    writing-mode: vertical-rl;
    letter-spacing: 0.5em;
  }

  .concept_message .message_02 {
    font-family: "YuKyokasho",sans-serif;
    font-size: 25px;
    position: absolute;
    right: 85px;
    top: 140px;
    color: #fff9ec;
    writing-mode: vertical-rl;
    letter-spacing: 0.5em;
  }

  /* Enjoy organic */
  #content01 {
    padding: 30px 30px;
    background-color: #805320;
  }

  .title {
    /* font-family: "Playfair Display",serif; */
    color: #fff9ec;
    font-family: "Caveat","Playfair Display",serif;
    font-size: 40px;
    text-align: center;
  }

  .sab_title {
    font-family: "YuKyokasho",sans-serif;
    font-size: 15px;
    text-align: center;
    color: #fff9ec;
  }

  .message_03 {
    padding: 40px 0;
  }

  .message_04 {
    font-family: "YuKyokasho",sans-serif;
    font-size: 20px;
    color: #fff9ec;
  }

  #button_01 {
    color: #fff9ec;
    display: block;
    margin: auto;
    border: none;
    border-radius: 2px;
  }

  .button_message_01 {
    color: #805320;
    font-family: "Playfair Display",serif;
    font-size: 15px;
    padding: 8px 10px;
  }

  /* Healthy Food */
  #content02 {
    padding: 30px 30px;
    background-color: #C28643;
  }

  .pic_1 {
    width: 100%;
    position: relative;
    z-index: 1;
    padding: 30px 0;
  }

  .pic_2 {
    width: 85%;
    position: absolute;
    opacity: 0.3;
    left: 56px;
    padding-top: 90px;
  }

  #button_02 {
    color: #fff9ec;
    display: block;
    margin-left: auto;
    border: none;
    border-radius: 2px;
  }

  .button_message_02 {
    color: #805320;
    font-family: "Playfair Display",serif;
    font-size: 15px;
    padding: 8px 25px;
  }

  .messages {
    padding-top: 20px;
  }

  .button_content {
    padding-bottom: 50px;
  }

  /* Blog */
  .cercle {
    display: flex;
    justify-content: space-between;
  }

  .cercle_1 {
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background-color: #fff9ec;
    box-shadow: 0 2px 4px 0 rgba(0, 0, 0, .5);
  }

  .cercle_2 {
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background-color: #fff9ec;
    box-shadow: 0 2px 4px 0 rgba(0, 0, 0, .5);
  }

  .blog_content {
    padding: 0 25px;
  }

  .title_02 {
    color: #fff9ec;
    font-family: "Caveat","Playfair Display",serif;
    font-size: 40px;
    text-align: center;
    border-bottom: solid 2px #fff9ec;
  }

  .blog_contents {
    padding-left: 30px;
    padding-right: 30px;
    margin-top: 20px;
    color: #fff9ec;
    font-family: "YuKyokasho",sans-serif;
    font-size: 20px;
  }

  .blog_title {
    font-weight: bold;
  }

  .message_05 {
    border-bottom: solid 1px #fff9ec;
    padding-top: 15px;
    padding-bottom: 15px;
  }

  .message_06 {
    padding-left: 30px;
    padding-right: 30px;
    color: #fff9ec;
    font-family: "YuKyokasho",sans-serif;
    font-size: 20px;
  }

  /* Recruitment */

  .box {
    margin: 30px 0;
    background-color: #fff9ec;
  }

  .pic_3 {
    width: 80%;
    display: block;
    margin: auto;
    padding-top: 50px;
  }

  .message_04_02 {
    color: #805320;
    font-family: "YuKyokasho",sans-serif;
    font-size: 20px;
    padding: 0 50px;
  }

  .message_05_02 {
    color: #805320;
    font-family: "YuKyokasho",sans-serif;
    font-size: 20px;
    padding: 10px 50px;
  }

  .message_05_02 span {
    color: #805320;
    font-family: "Playfair Display",serif;
  }

  #button_03 {
    background-color: #805320;
    display: block;
    margin-left: auto;
    border: none;
    border-radius: 2px;
  }

  .button_message_03 {
    color: #fff9ec;
    font-family: "Playfair Display",serif;
    font-size: 15px;
    padding: 8px 25px;
  }

  .button_content_02 {
    padding-bottom: 50px;
    padding-right: 50px;
  }

  /* Contact */
  .pic_4 {
    width: 100%;
    padding-top: 20px;
  }

  /* Footer */

  footer {
    background-color: #805320;
    color: #fff9ec;
    font-family: "YuKyokasho",sans-serif;
    padding: 30px 40px;
  }

  #footer_logo .store_logo {
    font-size: 26px;
  }

  #footer_link {
    display: block;
    color: #fff9ec;
    font-family: "Playfair Display",serif;
    padding: 60px 0;
  }

  ul {
    padding: 0;
  }

  li {
    list-style: none;
    font-size: 18px;
    padding-bottom: 15px;
  }

  .store_access_02 {
    display: flex;
    justify-content: space-between;
  }

  .address_word {
    padding-bottom: 20px;
  }

  .address {
    padding-right: 20px;
  }
  
  .access_word {
    padding-bottom: 20px;
  }

  .access {
    padding-bottom: 20px;
    padding-right: 40px;
  }

  .phone_number_word {
    padding-bottom: 20px;
  }

  .phone_number {
    padding-right: 105px;
  }

  .sns_footer {
    padding: 50px 0;
  }

  .sns_btns img {
    padding-right: 3px;
  }

 }

