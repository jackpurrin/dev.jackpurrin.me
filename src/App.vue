<script>
export default {
  data() {
    return {
      msg: 'Hello World!'
    }
  }
}
</script>

<template>
  <h1>{{ msg }}</h1>
  <input v-model="msg">
</template>