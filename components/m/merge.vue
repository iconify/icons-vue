<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua5i5abkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:merge" /></template>
<style>
.ua5i5abkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3.5h.75A2.625 2.625 0 0 1 8.5 6.125v.75A2.625 2.625 0 0 1 5.875 9.5h-.75A2.625 2.625 0 0 1 2.5 6.875v-.75A2.625 2.625 0 0 1 5.125 3.5m0 11h.75A2.625 2.625 0 0 1 8.5 17.125v.75A2.625 2.625 0 0 1 5.875 20.5h-.75A2.625 2.625 0 0 1 2.5 17.875v-.75A2.625 2.625 0 0 1 5.125 14.5M18 8.5za3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-3.5 3.5a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 18 8.5m-9.5-2h1a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-1m3-5.5h3");
}

</style>
