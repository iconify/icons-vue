<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jt2tn6g0v"/><path class="juj6a7bmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:overgrown-hedge" /></template>
<style>
.jt2tn6g0v {
  d: path("M3 20v-6c0-2.5 2-4 4-3.5c1-2 3.5-2.5 5-1.5c1.5-1 4-.5 5 1.5c2-.5 4 1 4 3.5v6Z");
}

.juj6a7bmr {
  d: path("M7 10.5q.5-4.5-4-5q-.5 4.5 4 5Zm10 0q-.5-5.5 4-7q1 5.5-4 7ZM12 9V5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
