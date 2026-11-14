<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnb2m2ffe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snow-racer" /></template>
<style>
.dnb2m2ffe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5v4H18M3 18h15.5a2.5 2.5 0 0 0 2.5-2.5m-14.5-2V18m6-4.5V18m3.5-4.5V5m-2.25 0h4.5");
}

</style>
