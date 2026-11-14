<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cazp75dmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stent" /></template>
<style>
.cazp75dmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5h14m-14 11h14M17 12a2 5.5 0 1 0 4 0a2 5.5 0 1 0-4 0M5 6.5C3.75 6.5 3 9 3 12s.75 5.5 2 5.5m0-11l5.5 11m0-11L5 17.5m5.5-11l5.5 11m0-11l-5.5 11");
}

</style>
