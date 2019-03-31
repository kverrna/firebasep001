<template>
   <button v-on:click="count++">Você clicou em mim {{ count }} vezes.</button> 
</template>

<script>
  export default {
    data: function () {
        return {
        count: 0
        }
    }
  }
</script>