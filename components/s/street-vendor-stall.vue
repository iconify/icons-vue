<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt2ig9weg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:street-vendor-stall" /></template>
<style>
.xt2ig9weg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9l2.5-5.5h13L21 9M3 9a2.25 2.25 0 0 0 4.5 0A2.25 2.25 0 0 0 12 9a2.25 2.25 0 0 0 4.5 0A2.25 2.25 0 0 0 21 9M5 12v9m14-9v9M3 16h18");
}

</style>
