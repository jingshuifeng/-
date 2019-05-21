<template>
  <sjld :citys="citys" :sheng="sheng" @change="change"></sjld>
</template>

<script>
export default {
data(){
  return{
  citys:['1','2'],
  sheng:['3','4']
  }
},
methods:{
  change(e){
  console.log(e);
}
}
}
</script>

<style>

</style>
