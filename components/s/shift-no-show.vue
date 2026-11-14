<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw-xlnbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shift-no-show" /></template>
<style>
.kw-xlnbkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.165 2.653a4.5 4.5 0 0 1 3.182 3.182m0 2.33a4.5 4.5 0 0 1-3.182 3.182m-2.33 0a4.5 4.5 0 0 1-3.182-3.182m0-2.33a4.5 4.5 0 0 1 3.182-3.182m-6.51 18.768a7.75 7.75 0 0 1 2.489-4.68m2.535-1.524a7.75 7.75 0 0 1 5.302 0M18 14.5V18m0 3h.01");
}

</style>
