<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t-d1-dzhq"/><path class="xd3fvew_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:outdoor-stage" /></template>
<style>
.t-d1-dzhq {
  d: path("M2.5 13a9.5 9.5 0 0 1 19 0m-19 0h19v3h-19Zm3 3v4.5m13-4.5v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xd3fvew_d {
  d: path("M6 13a6 6 0 0 1 12 0");
}

</style>
