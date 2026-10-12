<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chksq5obg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sandbox-kids" /></template>
<style>
.chksq5obg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.5h5.5q1 0 .84.99l-.68 4.27q-.16.99-1.16.99h-3.5q-1 0-1.16-.99l-.68-4.27q-.16-.99.84-.99m-.5 0a3.25 3.25 0 0 1 6.5 0m4-4.75h2.5m-1.25 0V10m-1.5 0h3v2.75a1.5 1.5 0 0 1-3 0ZM2.75 21.25C4.5 17.75 7.75 16 12 16s7.5 1.75 9.25 5.25Z");
}

</style>
