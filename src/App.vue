<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Felipe Foto" class="felipePhoto" src="@/assets/felipe.jpg" width="300" height="300" />

    <div class="wrapper">
      <HelloWorld msg="Felipe Rodrigues" />

      <nav>
          <img class= "javaicon" src="@/assets/javaicon.png" alt="Java">
          <img class= "goicon" src="@/assets/goicon.png" alt="Go">
          <img class= "vueicon" src="@/assets/vueicon.png" alt="Vue">
          <img class= "mysqlicon" src="@/assets/mysql.png" alt="MySQL">
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
.felipePhoto {
  margin: auto;
  border-radius: 10px;
  margin-left: 7px;
}
.javaicon {
  width: 50px;
  margin-left: 50px;
}
.goicon {
  width: 50px;

}
.vueicon {
  width: 50px;
}
.mysqlicon {
  width: 50px;
  margin-left: 7px;
  margin-bottom: -7px;

}

</style>
