<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f65dfvv4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pit-closed-sign" /></template>
<style>
.f65dfvv4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5za2 2 0 0 1 2 2v11.5a2 2 0 0 1-2 2a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2m3.75 1h11a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 19.75 11h-11A1.75 1.75 0 0 1 7 9.25v-1.5A1.75 1.75 0 0 1 8.75 6M11 11l2.5-5m2.5 5l2.5-5");
}

</style>
