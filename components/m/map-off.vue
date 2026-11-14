<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssybbdc_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-off" /></template>
<style>
.ssybbdc_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.892 3.962L9 3.5L15 6l6-2.5v13.6m-4.892 2.938L15 20.5L9 18l-6 2.5V6.9m6-3.4v1.6m0 7.8V18m6-12v5.1m0 7.8v1.6M3.5 3.5l17 17");
}

</style>
