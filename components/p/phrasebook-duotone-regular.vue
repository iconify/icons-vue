<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bazq81bsf"/><path class="hwy5g2bde"/><path class="emxd-h1xw"/><path class="d3xn50bni"/><path class="oy7fa3gbk"/><path class="m0wg_2sjy"/><path class="xoh5qp2um"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:phrasebook-duotone-regular" /></template>
<style>
.bazq81bsf {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.emxd-h1xw {
  fill: currentColor;
  d: path("M11 14v4h3.5v-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hwy5g2bde {
  fill: currentColor;
  d: path("M11 7v4h3.5V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m0wg_2sjy {
  d: path("M11 7v4h3.5V7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oy7fa3gbk {
  d: path("M8 2v20");
}

.xoh5qp2um {
  d: path("M11 14v4h3.5v-4Z");
}

</style>
