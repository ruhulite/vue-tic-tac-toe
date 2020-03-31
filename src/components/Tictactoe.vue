<template>
  <section>
    <h2>A simple Tic Tac Toe</h2>
    <div class="game--container">
      <div data-cell-index="0" class="cell"></div>
      <div data-cell-index="1" class="cell"></div>
      <div data-cell-index="2" class="cell"></div>
      <div data-cell-index="3" class="cell"></div>
      <div data-cell-index="4" class="cell"></div>
      <div data-cell-index="5" class="cell"></div>
      <div data-cell-index="6" class="cell"></div>
      <div data-cell-index="7" class="cell"></div>
      <div data-cell-index="8" class="cell"></div>
    </div>
    <h2 class="game--status"></h2>
    <button class="game--restart">Restart Game</button>
  </section>
</template>

<script>
export default {
  name: 'HelloWorld',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import '../assets/css/style.css';
</style>
