<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m16usewkl"/><path class="ixc9itwgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:street-light-report" /></template>
<style>
.ixc9itwgo {
  d: path("M11.5 3h8l-2 3.5h-4Zm3 10.5H18l3.5 3.5v4.5h-7Zm2.25 5.5h2.5");
}

.m16usewkl {
  d: path("M3.5 21h6m-3 0V9m0 0a6 6 0 0 1 6-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
