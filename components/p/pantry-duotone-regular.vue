<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hx31bvbvo"/><path class="mbt4yzbhr"/><path class="xqgf1x8se"/><path class="fcr9kzbtf"/><path class="k187sabpz"/><path class="z9ittvbis"/><path class="mia87q3wc"/><path class="a1mgubcgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pantry-duotone-regular" /></template>
<style>
.a1mgubcgh {
  d: path("M13 19v-5h4v5");
}

.fcr9kzbtf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 19v-5h4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hx31bvbvo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 11h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k187sabpz {
  d: path("M2 11h20");
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mia87q3wc {
  d: path("M5 11V6h4v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xqgf1x8se {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11V6h4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
