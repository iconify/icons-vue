<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="log5jybmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pinched-nerve" /></template>
<style>
.log5jybmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 2.5h10.75A2.625 2.625 0 0 1 20 5.125v.75A2.625 2.625 0 0 1 17.375 8.5H6.625A2.625 2.625 0 0 1 4 5.875v-.75A2.625 2.625 0 0 1 6.625 2.5m0 13h10.75A2.625 2.625 0 0 1 20 18.125v.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875v-.75A2.625 2.625 0 0 1 6.625 15.5M2.5 12h6l1.75-1.25l1.75 2.5l1.75-2.5L15.5 12h6");
}

</style>
