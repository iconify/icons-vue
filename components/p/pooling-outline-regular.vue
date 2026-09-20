<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tfto2zbdp"/><path class="xlz01ub4s"/><path class="ml5vh8o3m"/><path class="n_1n94xtx"/><path class="godgg2x3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pooling-outline-regular" /></template>
<style>
.godgg2x3f {
  d: path("M8 16.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.ml5vh8o3m {
  d: path("M17 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n_1n94xtx {
  d: path("M9.5 8.5 12 11l2.5 -2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tfto2zbdp {
  d: path("M5 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xlz01ub4s {
  d: path("M11 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
