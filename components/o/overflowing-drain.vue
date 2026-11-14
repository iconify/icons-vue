<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgcqh2blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overflowing-drain" /></template>
<style>
.lgcqh2blv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17a9 4 0 1 0 18 0a9 4 0 1 0-18 0m5.5-1.25v2.5m3.5-2.5v2.5m3.5-2.5v2.5M3 3.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0m-18 5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
