<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_wabgou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signal-flare" /></template>
<style>
.yn_wabgou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 11h4v10.5h-4Zm2-8q3.75 3.75 1.5 6h-3Q8.25 6.75 12 3ZM6 5l1.5 1.5M18 5l-1.5 1.5M5.5 10H7m11.5 0H17");
}

</style>
