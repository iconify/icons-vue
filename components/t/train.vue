<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m-3pvccbv"/><path class="j3akw_70p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train" /></template>
<style>
.j3akw_70p {
  fill: currentColor;
  d: path("M10 13.5C10 14.3284 9.3284 15 8.5 15C7.6716 15 7 14.3284 7 13.5C7 12.6716 7.6716 12 8.5 12C9.3284 12 10 12.6716 10 13.5ZM17 13.5C17 14.3284 16.3284 15 15.5 15C14.6716 15 14 14.3284 14 13.5C14 12.6716 14.6716 12 15.5 12C16.3284 12 17 12.6716 17 13.5Z");
  stroke: none;
}

.m-3pvccbv {
  d: path("M7 2L17 2C18.6569 2 20 3.3431 20 5L20 15C20 16.6569 18.6569 18 17 18L7 18C5.3431 18 4 16.6569 4 15L4 5C4 3.3431 5.3431 2 7 2ZM4 9L20 9M4 5L2 5M20 5L22 5M7 18L5 22M17 18L19 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
