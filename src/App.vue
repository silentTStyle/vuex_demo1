<template>
  <my-addition></my-addition>
  <p>-----------------------------------</p>
  <my-subtraction></my-subtraction>
</template>

<script>
import Addition from './components/MyAdditon.vue'
import Subtraction from './components/MySubtraction.vue'

export default {
  name: 'App',

  components: {
    'my-addition': Addition,
    'my-subtraction': Subtraction
  }
}
</script>

<style lang="less" scoped></style>
