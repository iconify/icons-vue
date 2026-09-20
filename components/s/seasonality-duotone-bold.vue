<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o7dq6ibao"/><path class="oijfjacqq"/><path class="gam3cw54g"/><path class="h06k0cc0f"/><path class="e06a2yh0n"/><path class="ys-dg812g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:seasonality-duotone-bold" /></template>
<style>
.e06a2yh0n {
  d: path("M11 12a4 4 0 0 1 8 0");
}

.gam3cw54g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h06k0cc0f {
  d: path("M3 12a4 4 0 0 1 8 0");
}

.o7dq6ibao {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oijfjacqq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
