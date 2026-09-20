<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qlh7h_mau"/><path class="g2d135r0l"/><path class="yd1dd2b-v"/><path class="h06k0cc0f"/><path class="e06a2yh0n"/><path class="ys-dg812g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:seasonality-duotone-thin" /></template>
<style>
.e06a2yh0n {
  d: path("M11 12a4 4 0 0 1 8 0");
}

.g2d135r0l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h06k0cc0f {
  d: path("M3 12a4 4 0 0 1 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qlh7h_mau {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yd1dd2b-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
