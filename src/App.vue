<script>
  import AppTitle from './components/AppTitle.vue'
  import AppHero from './components/AppHero.vue'


  export default{
    components: { AppTitle, AppHero },
    data (){
      return{
        
      }
    }

  }
</script>

<template>

  <div class="container text-success mt-0">

    <h1><u><AppTitle></AppTitle> </u></h1>


    <div class="mt-3">

      <AppHero></AppHero>
      
    </div>

  </div>
  
 
</template>

<style>

</style>
