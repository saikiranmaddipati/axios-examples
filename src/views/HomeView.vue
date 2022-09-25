<template>
  <div class="home">
    <post-details></post-details>
  </div>
</template>

<script>
// @ is an alias to /src
import PostDetails from '../components/PostDetails.vue'

export default {
  name: 'HomeView',
  components: {
    PostDetails
  }
}
</script>
