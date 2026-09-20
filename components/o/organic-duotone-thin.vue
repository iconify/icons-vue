<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhy5nnbig"/><path class="lpfdprsco"/><path class="o_ssmh9ez"/><path class="hc_p61b5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:organic-duotone-thin" /></template>
<style>
.hc_p61b5u {
  d: path("M7 17c0 -6 4 -10 10 -10 0 6 -4 10 -10 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpfdprsco {
  fill: currentColor;
  d: path("M7 17c0 -6 4 -10 10 -10 0 6 -4 10 -10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.zhy5nnbig {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
