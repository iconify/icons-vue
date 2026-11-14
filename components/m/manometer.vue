<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kxr_cubdx"/><path class="po0yzv23k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:manometer" /></template>
<style>
.kxr_cubdx {
  d: path("M4.5 3v10.5a7.5 7.5 0 0 0 15 0V3");
}

.po0yzv23k {
  d: path("M8 3v10.5a4 4 0 0 0 8 0V3M4.5 12H8m8-5.5h3.5M10.75 5h2.5M11.5 8.25h1.75m-2.5 3.25h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
