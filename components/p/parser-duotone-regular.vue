<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hd0bezdcu"/><path class="zw1m3v58r"/><path class="c1e5b9b_i"/><path class="fgp9a0qmd"/><path class="f-x5yl3mg"/><path class="usiycnb-x"/><path class="hwv-lccbz"/><path class="xyhj-ubbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parser-duotone-regular" /></template>
<style>
.c1e5b9b_i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 7h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f-x5yl3mg {
  d: path("M2 12h11");
}

.fgp9a0qmd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hd0bezdcu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hwv-lccbz {
  d: path("M13 7h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.usiycnb-x {
  d: path("M13 7v10");
}

.xyhj-ubbr {
  d: path("M13 17h7");
}

.zw1m3v58r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
