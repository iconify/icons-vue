<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyzn63nhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:static-electricity" /></template>
<style>
.dyzn63nhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3 9c0-1.25 2.75-2.25 7-2.25s7 1 7 2.25m-7-13V3M7.25 9.5V5m5.5 4.5V5m6.75-1.5L17 8h3l-2.5 4.5");
}

</style>
