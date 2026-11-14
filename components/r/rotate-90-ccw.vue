<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="glxk8db1y"/><path class="bcubxb6dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rotate-90-ccw" /></template>
<style>
.bcubxb6dz {
  d: path("M3.75 11.75L6.5 14.5l2.75-2.75");
}

.glxk8db1y {
  d: path("M11.5 10h9v9h-9Zm-5 4.5A9.5 9.5 0 0 1 16 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
