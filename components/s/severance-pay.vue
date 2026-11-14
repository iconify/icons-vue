<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvvar1bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:severance-pay" /></template>
<style>
.rvvar1bua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h18v9.5H3Zm10-3.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-1v2M8 12V6.5M8 9c0-2-1.5-3.5-3.5-3.5C4.5 7.5 6 9 8 9Zm0-1.5c0-2.25 1.5-3.75 3.5-3.75c0 2-1.5 3.75-3.5 3.75ZM3 12L2 9.5M21 12l1-2.5");
}

</style>
