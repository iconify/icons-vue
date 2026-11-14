<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb583ac3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neck-pillow" /></template>
<style>
.xb583ac3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 19C3 19 3 9 7 6c2-1.5 8-1.5 10 0c4 3 4 13 0 13c-2 0-2-5-5-5s-3 5-5 5Z");
}

</style>
