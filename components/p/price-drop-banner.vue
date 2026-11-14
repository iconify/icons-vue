<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lly5mtasd"/><path class="qmtcpccsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-drop-banner" /></template>
<style>
.lly5mtasd {
  d: path("M2.5 2.5h19M4.5 6h15L12 20.5ZM7 2.5V6m10-3.5V6m-5 2.75V14");
}

.qmtcpccsb {
  d: path("M9.75 11.75L12 14l2.25-2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
