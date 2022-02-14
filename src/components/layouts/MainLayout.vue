<template lang="ts">
  <div>
    <Header/>
    <div class="mainLayoutDiv">
      <Menu/>
      <MainContent/>
    </div>
  </div>
</template>
<script>

import Header from '../header/Header.vue'
import Menu from '../menu/Menu.vue'
import MainContent from './MainContent.vue'
export default {
  name: "MainLayout",
  components: {
    Header,
    Menu,
    MainContent
  }
}
</script>
<style scoped>

  .mainLayoutDiv {
    display: flex;
  }
</style>