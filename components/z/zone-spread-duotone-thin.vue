<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhy5nnbig"/><path class="eg3m9orpz"/><path class="r5z-jroyn"/><path class="wimmg3bgi"/><path class="o_ssmh9ez"/><path class="lufxq7bjk"/><path class="pbh8k3r0o"/><path class="ly2b2eaue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:zone-spread-duotone-thin" /></template>
<style>
.eg3m9orpz {
  fill: currentColor;
  d: path("M6.5 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lufxq7bjk {
  d: path("M6.5 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ly2b2eaue {
  d: path("M8.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.pbh8k3r0o {
  d: path("M14 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.r5z-jroyn {
  fill: currentColor;
  d: path("M14 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wimmg3bgi {
  fill: currentColor;
  d: path("M8.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zhy5nnbig {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
