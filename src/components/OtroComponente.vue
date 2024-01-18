<template>
    <div>
      <h1 class="green">{{ msg }}</h1>
      <h2>ESTÁS EN Otro componete</h2>
      <h3>
        Este es el cuerpo del componente que se carga DENTRO de HelloWorld    
      </h3>
    </div> 
  </template>

<script>
  export default {
      name: 'OtrComponente',
      components: {},
      props: {
        msg: {
          type: String,
          required: true
        }
      },
      data(){
          return{

          }
      },
      methods:{
          
      }
  }
</script>

<style scoped>
div{
 border: solid 1px red;   
}
</style>


