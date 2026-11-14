<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2hbxcooz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:taiyaki" /></template>
<style>
.v2hbxcooz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12c2-4 6.5-5 11-3.5c2 .5 3 1.5 3 3.5s-1 3-3 3.5C9.5 17 5 16 3 12Zm14 0l4.5-3.5v7ZM7 11h.01");
}

</style>
