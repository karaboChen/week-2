<script setup>
</script>

<template>
  <!-- one -->
  <div class="container">
    <div class="navbar box">
      <a href="#">WILLIAM LEE</a>
      <a href="#">BASED IN TAIWAN</a>
      <a href="#">CURRENTLY FRONT END ENGINEER AT HEXSCHOOL</a>
      <a href="#">CONTACT ME</a>
    </div>
    <div class="info box">
      <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/people.png?raw=true" alt="人">
      <div>
        <p class="info_txt">Hi</p>
        <p class="info_txt">I’m a front-end developer</p>
        <div style="text-align: end;">
          <p class="person_name">William</p>
        </div>
        <div class="bg_flex">
          <a href="#">contact me</a>
          <img
            src="https://raw.githubusercontent.com/hexschool/2022-web-layout-training/ec12423281aab560a26016d3cd5175f97e1e7e26/2023week2/arrow_outward.svg"
            alt="">
        </div>
      </div>
    </div>
  </div>
  <!-- two -->
  <div class="img_container">
    <div class="intr box">
      <section class="intr_txt">
        <h3>Introduction</h3>
        <h4>Hi, I'm William Lee, a Front-End Developer with a passion for building beautiful and responsive websites that
          provide an optimal user experience.</h4>
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/sparkle-sm.png?raw=true"
          alt="">
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/sparkle-sm.png?raw=true"
          alt="">
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/sparkle-sm.png?raw=true"
          alt="">
      </section>
      <!-- 大臨行 -->
      <section>
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/sparkle.png?raw=true" alt="">
      </section>
      <!-- 香雞 -->
      <section>
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/photographer.png?raw=true"
          alt="">
      </section>
      <!-- 人 -->
      <section>
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/people-2.png?raw=true" alt="">
      </section>

    </div>
  </div>
  <!-- three -->
  <div class="About box ">
    <div class="left">
      <div class="left_item">
        <p>01</p>
        <h4>Attention to Detail</h4>
        <h5>Meticulous code analysis and optimization.</h5>
      </div>
      <div class="left_item">
        <p>02</p>
        <h4>Adaptability</h4>
        <h5>Swift learning of new technologies.</h5>
      </div>
      <div class="left_item">
        <p>03</p>
        <h4>Problem Solver</h4>
        <h5>Identifying and resolving issues.</h5>
      </div>
      <div class="left_item">
        <p>04</p>
        <h4>Team Player</h4>
        <h5>Collaborates and shares ideas.</h5>
      </div>
    </div>
    <div class="right">
      <h3>About Me</h3>
      <h4>With over 5 years of experience, I'm proficient in HTML, CSS, JavaScript, jQuery, and React. I have a strong
        understanding of user experience design and accessibility. I'm always learning new technologies and techniques to
        stay up-to-date in the field.</h4>
    </div>
  </div>
  <!-- four -->
  <div class="contact">
    <div class="box  contact_box">
      <div class="contact_left">
        <h3>CONTACT ME</h3>
        <img
          src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/trending_flat_black_24dp%201.png?raw=true"
          alt="">
      </div>
      <div class="contact_right">
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/discord.png?raw=true"
          alt="dis">
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/instagram.png?raw=true"
          alt="ig">
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/message.png?raw=true" alt="">
      </div>
    </div>
  </div>
  <!-- five -->
  <div class="pics box">
    <h3>My Projects</h3>
    <div class="pic_container">
      <div class="pics_left">
        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/Rectangle%2010.png?raw=true"
          alt="">
      </div>
      <div class="pics_right">
        <div class="small_box">
          <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/Rectangle%2015.png?raw=true" alt="">
          <div class="small_txt">
            <h5>I've worked on a variety of websites, including e-commerce sites, blogs, and landing pages. I take pride in creating clean, efficient, and user-friendly code.</h5>
            <div class="small_bg">
              <a href="#">SEE MORE</a>
              <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/arrow_outward-white.png?raw=true" alt="">
            </div>
          
          </div>
        </div>
        <img class="phone" src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/Rectangle%2014.png?raw=true" alt="">
        <img class="note" src="https://github.com/hexschool/2022-web-layout-training/blob/main/2023week2/Rectangle%2029.png?raw=true" alt="">
      </div>
    </div>

  </div>
  <div class="footer container">
    <div class="box">
       <a href="#" class="email">all rights reserved @hexschool2023</a>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bruno+Ace&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bruno+Ace+SC&display=swap');
@import url('@/assets/one.css');
@import url('@/assets/two.css');
@import url('@/assets/three.css');
@import url('@/assets/four.css');
@import url('@/assets/five.css');

.footer{
  margin-top: 160px;
  text-align: center;
}
.email{
  display: block;
  text-decoration: none;
  color: white;
  padding: 40px 0px;
}

</style>
