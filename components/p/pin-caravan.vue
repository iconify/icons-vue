<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="de_7rqgba"/><path class="l7ko0ib4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-caravan" /></template>
<style>
.de_7rqgba {
  d: path("M14.8 14H5V4h15v8");
}

.l7ko0ib4j {
  d: path("M9 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM7.75 6.75h5V10h-5ZM2.5 13H5m14 9l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
