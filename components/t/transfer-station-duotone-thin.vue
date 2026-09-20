<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x4r46rbgt"/><path class="ior14cbcm"/><path class="zwqs38b8g"/><path class="cqzy_ibpe"/><path class="rw6ho_bav"/><path class="z9ittvbis"/><path class="d4colq8ps"/><path class="l6csbcieq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transfer-station-duotone-thin" /></template>
<style>
.cqzy_ibpe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 9 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d4colq8ps {
  d: path("m8 9 4 4 -4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ior14cbcm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l6csbcieq {
  d: path("m16 9 -4 4 4 4");
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.x4r46rbgt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

.zwqs38b8g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 9 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
