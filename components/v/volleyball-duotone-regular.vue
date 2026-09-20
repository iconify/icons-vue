<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zhy5nnbig"/><path class="o_ssmh9ez"/><path class="ljnnjibqo"/><path class="cjtncdbte"/><path class="t86ghs5dg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volleyball-duotone-regular" /></template>
<style>
.cjtncdbte {
  d: path("M3 15c4 -1 10 1 13 5");
}

.ljnnjibqo {
  d: path("M4 9c4 1 10 -1 13 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.t86ghs5dg {
  d: path("M9 3.5c2 4.5 2 12.5 0 17");
}

.zhy5nnbig {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
