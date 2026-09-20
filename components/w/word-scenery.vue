<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="u5enhobhu"/><circle class="ys3yu_69m"/><circle class="kmbhnbe3x"/><circle class="rvbovk3jn"/><path class="v30he_bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:word-scenery" /></template>
<style>
.kmbhnbe3x {
  cx: 38.333px;
  cy: 24px;
  r: 7.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rvbovk3jn {
  cx: 9.667px;
  cy: 24px;
  r: 7.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u5enhobhu {
  cx: 24px;
  cy: 9.667px;
  r: 7.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v30he_bxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.734 18.932l4.198-4.198m14.334 14.334l-4.198 4.198m-14.334-4.198l4.198 4.198m2.418 9.067v-8h2.62c1.48 0 2.68 1.203 2.68 2.687s-1.2 2.687-2.68 2.687h-2.62m2.62-.001l2.62 2.625M28 5.667l-2 8l-2-8l-2 8l-2-8M35.683 28v-8h1.8a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5zM9.667 20za2.65 2.65 0 0 1 2.65 2.65v2.7a2.65 2.65 0 0 1-5.3 0v-2.7A2.65 2.65 0 0 1 9.667 20");
}

.ys3yu_69m {
  cx: 24px;
  cy: 38.333px;
  r: 7.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
