<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zr4fqjbaq"/><path class="stw0i5b1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-lock" /></template>
<style>
.stw0i5b1y {
  d: path("M6.5 11.5h5v4h-5Zm1 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zr4fqjbaq {
  d: path("M2.5 6h13v12h-13Zm13 4.5l6-3.5v10l-6-3.5Z");
}

</style>
