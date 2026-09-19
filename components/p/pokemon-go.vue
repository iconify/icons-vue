<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ee8w9sbdc"/><circle class="n6w3b0d3u"/><path class="q3qhweb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pokemon-go" /></template>
<style>
.ee8w9sbdc {
  cx: 23.99px;
  cy: 23.99px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n6w3b0d3u {
  cx: 23.99px;
  cy: 23.99px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q3qhweb2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.49 23.99h13m17 0h13");
}

</style>
