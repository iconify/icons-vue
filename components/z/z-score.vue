<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="egs8wo4ve"/><path class="xri2zz2wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:z-score" /></template>
<style>
.egs8wo4ve {
  d: path("M2.5 19.5c5 0 6-12.5 9.5-12.5s4.5 12.5 9.5 12.5m-9.5 0v2m2.5-2v2m2.5-2v2m0-13v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xri2zz2wl {
  fill: currentColor;
  d: path("M15.75 6.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
