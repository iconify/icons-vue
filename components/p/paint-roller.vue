<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vazw2kb5k"/><path class="f82ee-m1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paint-roller" /></template>
<style>
.f82ee-m1o {
  d: path("M18 5.25h2.5v5.5H12V14m-1.5 0h3v7.5h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vazw2kb5k {
  d: path("M3 2.5h15V8H3Z");
}

</style>
