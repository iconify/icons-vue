<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gax9dnbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-coins-percent" /></template>
<style>
.gax9dnbup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.1 21.5H3V16h9.7m0 0H5.5v-5.5h13v3.1M3 5h13v5.5H3Zm11.75 16.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
