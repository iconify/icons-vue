<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwh9tjs8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-courthouse" /></template>
<style>
.nwh9tjs8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 6.25l3.587-2.192a1.75 1.75 0 0 1 1.826 0L16.5 6.25A1.484 1.484 0 0 1 15.726 9H8.274A1.484 1.484 0 0 1 7.5 6.25M3 20.5h18M6.5 11.75v6m5.5-6v6m5.5-6v6");
}

</style>
