<template>
  <div>
    <h1>分析页</h1>
    <Header />
    <SiderMenu />
    <router-view></router-view>
    <Footer />
  </div>
</template>

<script>
import Header from "./Header";
import SiderMenu from "./SiderMenu";
import Footer from "./Footer";
export default {
  components: {
    Header,
    Footer,
    SiderMenu
  }
};
</script>

<style></style>
