<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="nshojsrrg"/><path class="bw-8x6bhe"/><path class="l1hiclb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yamaha" /></template>
<style>
.bw-8x6bhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.26 15.277l18.247 10.535c1.048.605 1.405 1.936.8 2.985s-1.937 1.405-2.986.8L11.075 19.061M34.978 30.34l-.548 1.92l5.235.785l-3.297-4.141zl-2.671-1.542");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l1hiclb1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.925 19.06L18.68 29.595c-1.049.605-2.38.248-2.985-.8s-.249-2.38.8-2.985L34.74 15.275M13.022 30.337l-1.39-1.435l-3.297 4.141l5.235-.784zl2.67-1.542");
}

.nshojsrrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.816 37.663v-21.07c0-1.21.975-2.184 2.186-2.184s2.185.974 2.185 2.185v21.07m-2.185-26.341l1.938-.485L24 5.912l-1.938 4.926zv3.085");
}

</style>
