<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpd9l4bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-carport" /></template>
<style>
.rpd9l4bjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.636 7.716l16.409-4.102A1.17 1.17 0 0 1 21.5 4.75v.329a1.5 1.5 0 0 1-1.136 1.455L3.955 10.636A1.17 1.17 0 0 1 2.5 9.5v-.329a1.5 1.5 0 0 1 1.136-1.455M4.5 10.5V21m14-14v14M7.25 20v-2.75l2-3h4.5l2 3V20Z");
}

</style>
