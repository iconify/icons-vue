<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oirb_t35x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sea-breeze" /></template>
<style>
.oirb_t35x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h12.5a2.5 2.5 0 0 0 0-5M3 12h10a2.5 2.5 0 0 1 0 5M3 19.25q1.75-1.5 3.5 0t3.5 0m3.5.5h8m-2-2l2 2l-2 2");
}

</style>
