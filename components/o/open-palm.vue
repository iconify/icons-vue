<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttxrt-brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:open-palm" /></template>
<style>
.ttxrt-brd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 11v4.5l-2.5-2.25A1.75 1.75 0 0 0 5 15.5l3.25 4a6 6 0 0 0 4.75 2a6 6 0 0 0 6-6v-4m-9-.5V5.5m3 5v-7m3 7V4m3 7.5v-5");
}

</style>
