<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
  beforeCreate() {
    this.$router.push("/ber/enquiries");
  }
};
</script>



<style scoped lang="less">
@import "../static/css/reset.css";
#app {
  width: 100%;
  height: 100%;
  // overflow: hidden;
}
html,
body,
#app {
  width: 100%;
  height: 100%;
  /* overflow: hidden; */
}
// @media screen and (max-width:1336px){
//   .bit .right{
//     margin-top: -633px;
//     margin-left: 217px;
// }
// }
</style>
