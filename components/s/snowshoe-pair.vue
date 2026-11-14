<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lruzxkbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snowshoe-pair" /></template>
<style>
.lruzxkbtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3c3 0 3.5 3.5 3.5 7c0 5-2 8.5-3.5 11C5 18.5 3 15 3 10c0-3.5.5-7 3.5-7m11 0c3 0 3.5 3.5 3.5 7c0 5-2 8.5-3.5 11C16 18.5 14 15 14 10c0-3.5.5-7 3.5-7M3.25 8h6.5M3.5 13h6m4.75-5h6.5m-6.25 5h6");
}

</style>
