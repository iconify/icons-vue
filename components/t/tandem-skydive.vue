<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6rwkglzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tandem-skydive" /></template>
<style>
.w6rwkglzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5c2-6.5 17-6.5 19 0q-9.5-3-19 0Zm3 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-9.75 7.5a2.75 2.75 0 0 1 5.5 0m3.5 0a2.75 2.75 0 0 1 5.5 0M6 12.5l-3.5-3m15.5 3l3.5-3");
}

</style>
