<template>
<main>
<div class="spacer layer1 flip"></div>
  <section>
    <h2>test</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corrupti libero consectetur tempora voluptatum fugit expedita accusamus obcaecati repellendus asperiores nobis harum, pariatur atque, sequi minima numquam nesciunt quibusdam aliquid illum.</p>
  </section>
<div class="spacer layer1"></div>
<div class="spacer layer2 flip"></div>
  <section class="blue">
    <h2>test</h2>
    <p>Veniam accusamus, voluptates cum quidem incidunt commodi nihil sint laudantium facere maxime beatae, modi dolores sunt earum eaque, natus laborum eveniet officia labore animi illo ex? Quam, vero! Voluptatem, quae!</p>
  </section>
  <div class="spacer layer2"></div>
</main>
</template>

<script>
export default {}
</script>
<style>
body {
  margin: 0;
  color: white;
  background: #3e4244;
}
section {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 400px;
  padding: 100px 20vw;
}
.spacer {
  aspect-ratio: 900/300;
  width: 100%;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.layer1 {
  background-image: url("/img/bg-1.svg");
}
.layer2 {
  background-image: url("/img/bg-2.svg");
}
.flip {
  transform: rotate(180deg);
}
.blue {
  background-color: #4b24c7;
}
.red {
  background-color: #da0101;
}
</style>
