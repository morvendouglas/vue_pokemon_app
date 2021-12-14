<template>
  <div id="pokemon-detail">
      <div>{{pokemon.name.toUpperCase()}}</div>
  <img :src="pokemon.sprites.front_shiny" />
  </div>
</template>

<script>
export default {
    name : "PokemonDetail",
    props: ["pokemon"]
};
</script>

<style>

</style>