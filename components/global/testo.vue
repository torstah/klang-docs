<template>
 <div>
   <button class="btn" @click="test">Test klang</button>

 </div>
</template>

<script>


export default {

  props: {
    options: {
      type: Array,
      default: () => []
    }
  },
  data () {
    return {
      value: null
    }
  },
  methods: {
    test(){
      alert("ping")
    }
  }
}
</script>

<style>

.btn {
  border: 1px solid gray;
  padding: 2rem;
}

</style>