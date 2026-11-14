<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kkgt4nb_x"/><path class="ac7elgm0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nesting-area" /></template>
<style>
.ac7elgm0n {
  d: path("M5.5 7.75a2.5 3.25 0 1 0 5 0a2.5 3.25 0 1 0-5 0m8 0a2.5 3.25 0 1 0 5 0a2.5 3.25 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kkgt4nb_x {
  d: path("M2.5 11h19M3 11c0 5.5 4 8.5 9 8.5s9-3 9-8.5");
}

</style>
