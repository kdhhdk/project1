<template>
  <div class="home">
    <input type="text" v-model="message">
    {{message}}
    <b-button variant="primary">Button</b-button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {

  },
  data () {
    return {
      message: '안녕'
    }
  }
}
</script>
