<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unsg7dbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-greenhouse" /></template>
<style>
.unsg7dbjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.485 20H2.5V10L9 3.5l6.5 6.5v.415M9 3.5V20M2.5 10h13m.5 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5-4.25v1m0 6.5v1m-4.25-4.25h1m6.5 0h1m-6.5-2.25l-.75-.75m5.25.75l.75-.75m-5.25 5.25l-.75.75m5.25-.75l.75.75");
}

</style>
