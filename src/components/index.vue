<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <a href="~/list">点击进入</a>
  </div>
</template>

<script>
export default {
  name: 'index',
  data () {
    return {
      msg: 'Welcome to Your Life Manage'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@keyframes myscale
{
0% {transform: scale(1)}
50% {transform: scale(1.4)}
100% {transform: scale(1)}
}
@keyframes textScroll
{
from {transform: rotate(-180deg)}
to {transform: rotate(0)}
}
h1 {
  font-weight: normal;
  margin-top: 220px;
  color:#42b983;
  animation: textScroll 2s 1;
}
a {
  display: inline-block;
  color:#fff;
  background-color: #42b983;
  width: 150px;
  height: 36px;
  text-align: center;
  line-height: 36px;
  border-radius: 3px;
  margin-top:150px;
  animation:myscale 2s infinite;
}
</style>
