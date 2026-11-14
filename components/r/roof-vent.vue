<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xfkpu2byp"/><path class="irjaribfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roof-vent" /></template>
<style>
.irjaribfd {
  d: path("M4.5 16v5.5h15V16m-5-4V9.5H17V14m-1.25-7.5v-4m-2 2l2-2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfkpu2byp {
  d: path("M2.5 17.5L12 10l9.5 7.5");
}

</style>
