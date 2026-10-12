<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh4pdx93r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:standby-power" /></template>
<style>
.yh4pdx93r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 9.58a6.5 6.5 0 1 0 8.5 0M9.5 5.5V12m9-9.25a3.5 3.5 0 1 0 2.75 5.5a3.25 3.25 0 0 1-2.75-5.5");
}

</style>
