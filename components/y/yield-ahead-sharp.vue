<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zgkgjc1lj"/><path class="c-isjib1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yield-ahead-sharp" /></template>
<style>
.c-isjib1p {
  d: path("M8.75 7.25h7.5l-.49.87l-3.27 5.76l-.49.87l-.49-.87l-3.27-5.76l-.49-.87z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zgkgjc1lj {
  d: path("M4.75 4h16.5l-.99 1.74l-7.27 12.77l-.99 1.74l-.99-1.74L3.74 5.74L2.75 4z");
}

</style>
