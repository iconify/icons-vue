<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pxv26obfu"/><path class="aqtmy5bfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:policy-certificate" /></template>
<style>
.aqtmy5bfz {
  d: path("m12 6.75l2.5 1V9.5c0 1.5-1.1 2.4-2.5 3c-1.4-.6-2.5-1.5-2.5-3V7.75ZM10 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1 1.75l-.75 2m2.75-2l.75 2");
}

.pxv26obfu {
  d: path("M2.5 4h19v12.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
