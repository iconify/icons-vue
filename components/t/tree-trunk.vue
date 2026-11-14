<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdw9ar34t"/><path class="i19gzxb0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tree-trunk" /></template>
<style>
.i19gzxb0d {
  d: path("M5 7v10.5l-2 3h18l-2-3V7M9 13v4m6-2.5v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdw9ar34t {
  d: path("M5 7a7 3 0 1 0 14 0A7 3 0 1 0 5 7Z");
}

</style>
