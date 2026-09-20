<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v_dlw1bwz"/><path class="mbt4yzbhr"/><path class="az481cbgr"/><path class="yuc2lmxqb"/><path class="rw6ho_bav"/><path class="z9ittvbis"/><path class="d4colq8ps"/><path class="l6csbcieq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transfer-station-duotone-regular" /></template>
<style>
.az481cbgr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 9 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d4colq8ps {
  d: path("m8 9 4 4 -4 4");
}

.l6csbcieq {
  d: path("m16 9 -4 4 4 4");
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.v_dlw1bwz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yuc2lmxqb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 9 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
