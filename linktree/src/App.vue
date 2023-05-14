<template>
  <div class="body">
    <h1 class="title">링크트리 만들기</h1>
    <div class="content">
      <div class="box">
        <a class="naver" href="https://www.naver.com/" target="_blank">네이버로 이동하기</a>
      </div>
      <a class="naver" id="ccc" href="https://marpple.shop/kr/chillcocktailclub?page=0" target="_blank">칠칵테일 클럽으로 이동하기</a>
    </div>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
.body {
  width: 100%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.title {
  color: maroon;
  user-select: none;
}
a {
  color: black;
}
.naver {
  color: pink;
}
#ccc {
  color: blue;
}
.board_category {

}
.category {

}
.box {
  width: 400px;
  height: 200px;
  background-color: #fff;
  text-align: center;
  margin-top: 50px;
}
.naver.name {
  margin-top : 50px;
}
</style>
