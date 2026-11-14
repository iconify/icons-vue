<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w5t7ypb8d"/><path class="v05ub2b7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-walking" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v05ub2b7k {
  d: path("m7.5 11l4-3l4 3.5");
}

.w5t7ypb8d {
  d: path("M11.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1 3.5l-2 6l3 3V21m-3-7.5l-2 4l-2.5 3");
}

</style>
