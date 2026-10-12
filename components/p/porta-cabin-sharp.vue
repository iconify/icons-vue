<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qbn9ahbbt"/><path class="sir4zkl9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:porta-cabin-sharp" /></template>
<style>
.qbn9ahbbt {
  d: path("M2.75 6.75h18.5v10.5H2.75z");
}

.sir4zkl9y {
  d: path("M5.75 9.75h5.5v2.75h-6V9.75zm8.75-.25h4v7.75h-4zM2.75 20.25h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
