<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qifws2bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pooling-grid-sharp" /></template>
<style>
.qifws2bde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7h10v10h-10zm5 0v10m-5-5h10m1.5-2L16 12l-1.75 2m3.5-4h3.5v4h-3.5z");
}

</style>
