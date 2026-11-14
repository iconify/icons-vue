<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7h03j-uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:steam-power" /></template>
<style>
.m7h03j-uv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 10h7.75a2.625 2.625 0 0 1 2.625 2.625v6.25a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 2.5 18.875v-6.25A2.625 2.625 0 0 1 5.125 10M9 15.75h12.5M9 10v11.5M6 7.25C4.5 5.75 7.5 4 6 2.5m6 4.75C10.5 5.75 13.5 4 12 2.5");
}

</style>
