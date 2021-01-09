<template>
  <div id="app">
    <h1>vue admin</h1>
    <button @click="test">点击</button>
    <router-view/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data () {
    return {
      a: 1,
      b: '2'
    }
  },
  methods: {
    test (): string {
      return this.b
    }
  }
})
</script>

<style lang="scss"></style>
