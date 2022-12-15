<template>
    <div>
       <center> <img src="../assets/luisa.jpeg"></center>
<DatosComponente />
    </div>
</template>
<script>
import DatosComponente from '@/components/DatosComponente.vue'
export default {
   name:'VistaunoVista',
components:{
    DatosComponente
}
}
</script>
<style scoped>
img{
    width: 140px;
    height: 170px;
    border: solid 4px;
}
</style>