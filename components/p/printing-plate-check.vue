<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oqtcpcc9q"/><path class="w0njjikgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:printing-plate-check" /></template>
<style>
.oqtcpcc9q {
  d: path("M14.271 21.5H6L3.5 19V5L6 2.5h12L20.5 5v7.264");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w0njjikgl {
  d: path("M8 11a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-4.75v9.5M6.25 11h9.5m-1 7l2 2L21 15.75");
}

</style>
