<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gcyp9ccho"/><path class="qam07-gzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:open-chiller" /></template>
<style>
.gcyp9ccho {
  d: path("M3.5 21.5V4h17v17.5m-17 0h17M3.5 7h17m-17 5.5h17M3.5 17h17");
}

.qam07-gzr {
  d: path("M6 9.5h2.5v3H6Zm4.75 0h2.5v3h-2.5Zm4.75 0H18v3h-2.5ZM6 14.25h2.5V17H6Zm7 0h4.5V17H13Zm-7.5 5h2m3.5 0h2m3.5 0h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
