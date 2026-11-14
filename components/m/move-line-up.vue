<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyd9jcc_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:move-line-up" /></template>
<style>
.zyd9jcc_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h10v4h-10Zm.5 8.5h9.5m-9.5 6h9.5m6-6.5V5m-2.75 2.75L18.5 5l2.75 2.75");
}

</style>
