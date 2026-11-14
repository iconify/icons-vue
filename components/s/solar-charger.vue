<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6jswtbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-charger" /></template>
<style>
.y6jswtbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h16.5L19 12.5H2.5ZM3.75 7.75h16.5m-7-4.75l-2.5 9.5m0 0v6.4m-3.25.6h2.7m9.3-5L15 18.75h3l-1.5 3l4.5-4.5h-3Z");
}

</style>
