<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh3u4pbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ticket-barcode" /></template>
<style>
.yh3u4pbcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h19v3.5a2.5 2.5 0 0 0 0 5V18h-19v-3.5a2.5 2.5 0 0 0 0-5Zm8 3.5v5m2.75-5v5m2.75-5v5");
}

</style>
