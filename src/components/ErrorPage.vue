<template>
  <center>
     <div class='error'>
       <div class="error-container">
        <h1 class="error-h">404 Error!</h1>
        <p class="oops">Oooops, it seems you are lost..</p>
        <router-link to="/">Go to Home Page</router-link>
     </div>
    </div>
  </center>
   
</template>

<script>
export default {
    
}
</script>
<style>
  .error {
    background-color: #222;
    height: 100vh;
    color: white;
  }
  .error-container {
    padding:100px;
  }
  .oops {
    padding: 30px;
  }
    
</style>