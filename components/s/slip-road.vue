<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_rqsnbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:slip-road" /></template>
<style>
.p_rqsnbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 2.5v19m-7-19V8m0 5v8.5m-10 0C3 15 7 11 13 8M8 21.5c0-4.5 2-7 5-8.5");
}

</style>
