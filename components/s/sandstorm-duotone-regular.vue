<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="phoqueozj"/><path class="korpu6bdk"/><path class="ruzkcfbee"/><path class="k0pdcpb4w"/><path class="kakiz1beo"/><path class="j3fr8pubv"/><path class="lmi4eb-oe"/><path class="igyz-cc5b"/><path class="zhhqt74pq"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sandstorm-duotone-regular" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.igyz-cc5b {
  d: path("M3 20a5 5 0 0 1 10 0");
}

.j3fr8pubv {
  d: path("M3 6h15");
}

.k0pdcpb4w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 20a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kakiz1beo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.korpu6bdk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lmi4eb-oe {
  d: path("M5 10h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.phoqueozj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ruzkcfbee {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zhhqt74pq {
  d: path("M13 20a4 4 0 0 1 8 0");
}

</style>
