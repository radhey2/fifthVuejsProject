<template>
 <div id="app">
  <h3>What is your favorite kind of taco?</h3>
  <p v-text="tacos"></p>
  <p>{{ tacos }}</p>
  <p><input v-model="tacos" /></p>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
    data() {
    return {
      tacos: 'I like Al Pastor tacos'
    }
  }
}
</script>
