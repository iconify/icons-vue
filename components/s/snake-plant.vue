<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7-867b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snake-plant" /></template>
<style>
.x7-867b9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 15.5c-1-4.5-2-7-3-8.75a.5.5 0 0 1 .75-.5C7 7.75 9 10.5 10 13.5c0-4.5 1-8 1.75-10.25a.25.25 0 0 1 .5 0C13 5.5 14 9 14 13.5c1-3 3-5.75 5.75-7.25a.5.5 0 0 1 .75.5c-1 1.75-2 4.25-3 8.75M5 15.5h14l-1.5 6h-11Z");
}

</style>
