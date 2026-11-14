<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h5sdg-nxe"/><path class="z8wd6jg7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:squeaky-toy" /></template>
<style>
.h5sdg-nxe {
  d: path("M6.5 9.75a4 4 0 1 1 5.5 0c1 1.75 4 2.5 6.5 1.75l2.75-2c.5 2.5.25 5.5-1.25 8c-1.5 2.25-4.5 3.25-8 3.25c-4.5 0-8-1.75-8-5.25C4 13 5.25 11 6.5 9.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8wd6jg7r {
  d: path("M5.5 6L3.25 7.5l2.5 1.25ZM10 6h.01M10 14.5c2 2 5 2 7 0");
}

</style>
