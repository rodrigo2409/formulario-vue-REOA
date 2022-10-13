<template>
  
  <div class="container mt-3">  
    <Header/>
    <Formulario/>
    <!-- para que los datos no se refresquen utilizamos eso comentario
    <form @submit.prevent="addUser">
      <div>
        <label>
        Nombre: <input v-model="nombre" type="text" placeholder="Nombre" required/>
        </label>
      </div>
      <div>
        
        <label>
        Edad: <input v-model="edad" type="number" min="15" max="80" placeholder="edad" required/>
        </label>
      </div>
      <div>
        <label>
        Correo: <input v-model="correo" type="email" placeholder="email@mail.com" required/>
        </label>
      </div>
  
      <button type="submit">Enviar</button>
    </form> -->

  </div>
</template>

<script>
  import Header from './assets/components/Header.vue';
  import Formulario from './assets/components/Formulario.vue';
  
  export default {
    components:{
    Header,
    Formulario,
    }
  }
</script>

<style scoped>
  div{
    margin: 0px, 2rem;
  }
</style>