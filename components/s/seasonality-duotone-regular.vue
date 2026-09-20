<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="raue1-0hj"/><path class="iotmhxbqq"/><path class="tbe304aqf"/><path class="h06k0cc0f"/><path class="e06a2yh0n"/><path class="ys-dg812g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:seasonality-duotone-regular" /></template>
<style>
.e06a2yh0n {
  d: path("M11 12a4 4 0 0 1 8 0");
}

.h06k0cc0f {
  d: path("M3 12a4 4 0 0 1 8 0");
}

.iotmhxbqq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.raue1-0hj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tbe304aqf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
