<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yg0tb1dba"/><path class="x3b9ab9vr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:race-retirement" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3b9ab9vr {
  d: path("M4.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm10 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-11-6.75C2.25 10 4.75 8 3.5 6C2.75 4.75 3 3.5 4 2.5M7 10C5.5 8 8.5 6 7 3.75");
}

.yg0tb1dba {
  d: path("M4.5 18.5h-2v-3l5.5-2l2.5-2.75h4l3 2.75l4 1v4h-2m-10 0h5");
}

</style>
