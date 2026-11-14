<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dsleywj5l"/><path class="i21_4obmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spade-suit" /></template>
<style>
.dsleywj5l {
  d: path("m12 2.5l-8 8.25a4.75 4.75 0 1 0 8 4.75a4.75 4.75 0 1 0 8-4.75Z");
}

.i21_4obmb {
  d: path("m12 14.5l2.75 6.5h-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
