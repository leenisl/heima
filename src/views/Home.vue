<template>
  <div class="home">
    {{$store.state.count}}
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'home',
  components: {

  },
  created () {
    console.log(this)
  }
}
</script>
