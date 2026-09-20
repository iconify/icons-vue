<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j5hk4ybky"/><path class="jvontbc6y"/><path class="h51gqww2n"/><path class="bm68p9f0y"/><path class="bwifmcccx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:saved-payment-duotone-regular" /></template>
<style>
.bm68p9f0y {
  d: path("M6.5 10.5v3");
}

.bwifmcccx {
  d: path("M14 7h7v10l-3.5 -3.5L14 17Z");
}

.h51gqww2n {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.j5hk4ybky {
  fill: currentColor;
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jvontbc6y {
  fill: currentColor;
  d: path("M14 7h7v10l-3.5 -3.5L14 17Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
