<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zeddubb4l"/><path class="pv_nvolvx"/><path class="ak9-k8bah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sparrow-sharp" /></template>
<style>
.ak9-k8bah {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6h.01");
}

.pv_nvolvx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.85 5.5L3.5 7l-1.18.59l1.28.16l2.5.5Zm-3.1 15.75h18.5M10 17.5v3.75m3-3.75v3.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zeddubb4l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.75C5.75 4.5 7.25 3 9.25 3s3.5 1.5 3.5 3.5V7c3 1 5.25 3.5 6.25 6.5l2 2.5l.679.951l-1.129-.251L17 15.5c-1.25 1.25-3 2-5 2c-3.75 0-6.5-2.5-6.5-6V9.417L6.75 7.75l-1-.467z");
}

</style>
