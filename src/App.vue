<template>
<div>
  <UpperCase/>
</div>
</template>

<script>

import UpperCase from './components/UpperCase'

export default {
  name: 'App',
  components: {
    UpperCase
  }
}
</script>

<style>
  *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body{
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
</style>
