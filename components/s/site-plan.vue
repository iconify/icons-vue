<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh9pdkbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:site-plan" /></template>
<style>
.yh9pdkbkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5V3h3.5m11 0H21v3.5M6.5 21H3v-3.5M10 3h4m7 7v3.6M13.2 21H10m-7-7v-4m10.2 5.5H6.5v-9h7V10h3v1.6m-1 5.9l2.5-3.25l2.5 3.25M16 21.75V19l4 2.75V19");
}

</style>
