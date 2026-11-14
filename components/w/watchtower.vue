<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfucynb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:watchtower" /></template>
<style>
.mfucynb0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5L12 3l6.5 4.5Zm3 0h7A1.5 1.5 0 0 1 17 9v1.5a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 10.5V9a1.5 1.5 0 0 1 1.5-1.5M8.25 12L6.5 21.5m9.25-9.5l1.75 9.5m-10-5h9");
}

</style>
