<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p9_bc8bri"/><path class="us-09pbdx"/><path class="b4e05pbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sunlight-window" /></template>
<style>
.b4e05pbbe {
  d: path("m9.25 14.75l-4 4");
}

.p9_bc8bri {
  d: path("M2.5 2.5h19v19h-19Zm9.5 0v19M2.5 12h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.us-09pbdx {
  fill: currentColor;
  d: path("M14.75 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
