<template>
  <div class="home">
    <Searchform />
  </div>
</template>

<script>
// @ is an alias to /src
import Searchform from '@/components/Searchform.vue'

export default {
  name: 'Home',
  components: {
    Searchform
  }
}
</script>
