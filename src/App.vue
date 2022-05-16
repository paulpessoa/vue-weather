<template>
    <div id="app">
      <main>
        <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search ..."/>
        </div>
      </main>
    </div>
</template>

<script>
// https://home.openweathermap.org/api_keys

export default {
    name: 'app',
    data () {
      return {
        api_key: 'b720c2d8764f53ecf466dcff89cc82de'
      }
    }

}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'montserrat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
}
</style>

