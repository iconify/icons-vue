<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m52f-6b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:road-resurfacing" /></template>
<style>
.m52f-6b-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 21.5l5-19m11.328 8.846L16.5 2.5M12 14V5.5m-3 3l3-3l3 3m2.262 6.211za.68.68 0 0 1 .678-.648h.12a.68.68 0 0 1 .678.648a1.19 1.19 0 0 0 .591.973l.013.007a1.19 1.19 0 0 0 1.137.026a.68.68 0 0 1 .901.263l.059.103a.68.68 0 0 1-.222.912a1.19 1.19 0 0 0-.546.998v.014a1.19 1.19 0 0 0 .546.998a.68.68 0 0 1 .222.912l-.059.103a.68.68 0 0 1-.901.263a1.19 1.19 0 0 0-1.137.026l-.013.007a1.19 1.19 0 0 0-.591.973a.68.68 0 0 1-.678.648h-.12a.68.68 0 0 1-.678-.648a1.19 1.19 0 0 0-.591-.973l-.013-.007a1.19 1.19 0 0 0-1.137-.026a.68.68 0 0 1-.901-.263l-.059-.103a.68.68 0 0 1 .222-.912a1.19 1.19 0 0 0 .546-.998v-.014a1.19 1.19 0 0 0-.546-.998a.68.68 0 0 1-.222-.912l.059-.103a.68.68 0 0 1 .901-.263a1.19 1.19 0 0 0 1.137-.026l.013-.007a1.19 1.19 0 0 0 .591-.973");
}

</style>
