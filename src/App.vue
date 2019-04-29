<template>
  <div>
    <TopNav />
    <Search />
    <MainNav />
  </div>
</template>

<script>
import TopNav from 'public/TopNav/index.vue'
import Search from 'public/Search/index.vue'
import MainNav from 'public/MainNav/index.vue'

export default {
  components: {
    TopNav,
    Search,
    MainNav
  }
}
</script>

<style>
.hello {
 color: red;
}
</style>
