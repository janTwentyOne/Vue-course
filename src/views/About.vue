<template>
  <div>
    {{food}}
    <span>233</span>
  </div>
</template>

<script>
export default {
  props: {
    food: {
      type: String,
      default: 'apple'
    }
  },
  data(){
    return {
    }
  },
  methods:{},
}
</script>
<style lang="stylus" scoped>
</style>
