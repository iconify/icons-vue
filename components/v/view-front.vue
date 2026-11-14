<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdt7gwlme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:view-front" /></template>
<style>
.wdt7gwlme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9h9v9h-9Zm0 0l3-3h9v9l-3 3m0-9l3-3m-19 7.5h4.25M4.25 11l2.5 2.5l-2.5 2.5");
}

</style>
