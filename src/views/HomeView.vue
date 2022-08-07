<template>
  <div class="home">
    <MyButton greet="hi"></MyButton>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
// import HelloWorld from '../components/HelloWorld.vue'
import MyButton from '../components/MyButton.vue'

export default Vue.extend({
  name: 'HomeView',

  components: {
    // HelloWorld,
    MyButton
  },
})
</script>
