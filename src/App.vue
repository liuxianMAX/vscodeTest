<template>
  <div>
    <my-addition></my-addition>
    <p>-------------------------------------</p>
    <my-subtraction></my-subtraction>
  </div>
</template>

<script>
import Addition from './components/Addition.vue'
import Subtraction from './components/Addition.vue'

export default {
  name: 'App',
  data() {
    return {}
  },
  components: {
    'my-addition': Addition,
    'my-subtraction': Subtraction,
  },
}
</script>
