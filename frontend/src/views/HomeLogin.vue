<template>
<div class="d-flex flex-column align-items-center">
    <h2 class="text-center subtitle pt-5 pb-4">Connexion</h2>
    <p class="text-center font-italic">Connectez-vous pour accéder au forum !</p>
    <ConnexionForm/>
</div>
</template>

<script>
import ConnexionForm from '../components/ConnexionForm'
export default {
  name: 'HomeLogin',
  components: {
  ConnexionForm
    }
}
</script>


<style scoped lang="scss">

</style>