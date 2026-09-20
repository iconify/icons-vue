<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tu3bv3eig"/><path class="uxahocbdu"/><path class="fd7ctcc_z"/><path class="yoftwf7ei"/><path class="gr1zxddav"/><path class="e2nq-yvbg"/><path class="ueskbccpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rose-duotone-regular" /></template>
<style>
.e2nq-yvbg {
  d: path("M12 15v6");
}

.fd7ctcc_z {
  fill: currentColor;
  d: path("M4 19c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gr1zxddav {
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tu3bv3eig {
  fill: currentColor;
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ueskbccpe {
  d: path("M4 19c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.uxahocbdu {
  fill: currentColor;
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yoftwf7ei {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
