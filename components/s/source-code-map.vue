<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h17jhuqzw"/><path class="o3yg2dkzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:source-code-map" /></template>
<style>
.h17jhuqzw {
  d: path("m2.5 5l6-2l7 2l6-2v16l-6 2l-7-2l-6 2Z");
}

.o3yg2dkzr {
  d: path("M9.75 9L7 12l2.75 3m4.5-6L17 12l-2.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
