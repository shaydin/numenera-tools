<template>
  <div id="homepage">
    <div class="mdl-card">
      <header class="mdl-card__title">
        <h2 class="mdl-card__title-text">Numenera Playground</h2>
      </header>
      <div class="mdl-card__media">

      </div>
      <div class="mdl-card__supporting-text">
        Welcome to my Numenera playground, full of tools and generators to help
        you run your Numenera game.
      </div>
      <div class="mdl-card__actions mdl-card--border">
        <mdl-button colored @click.native="$store.commit('toggleDrawer')">Get Started</mdl-button>
      </div>
    </mdl-card>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#homepage {
  display: flex;
  align-items: center;
  justify-content:center;
  height: 100%;
  margin-top: 5em;
}

.mdl-card {
  flex: none;
  min-width: 50%;
}

.mdl-card__media  {
  width: 100%;
  padding-bottom: 40%;
  background: url('../assets/images/MCG-Numenera-Raster.jpg') center / cover;
}
</style>
