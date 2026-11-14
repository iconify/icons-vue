<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ybvwamblh"/><path class="z77cz-bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:press-vest" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ybvwamblh {
  d: path("M8.5 2.5H10L12 6l2-3.5h1.5c.25 3.5 1.5 6 4 7V20a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20V9.5c2.5-1 3.75-3.5 4-7Z");
}

.z77cz-bdw {
  d: path("M8 12.5h8V17H8Z");
}

</style>
