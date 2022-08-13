<template>
  <div id="app">
    <randomgifcat></randomgifcat>
  </div>
</template>

<script>
import RandomGifCat from "./components/RandomGifComponent.vue"
export default {
  name: 'component-name',

  data: function () {
    return {
      message: 'Random Gif Cat',
    }
  },

  methods: {

  },
  components: {
    'randomgifcat': RandomGifCat,
  },
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}
</style>
