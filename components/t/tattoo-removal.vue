<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_9762bos"/><path class="bugs33b0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tattoo-removal" /></template>
<style>
.bugs33b0j {
  d: path("m15.75 8.25l3.5-3.5M13.5 6L17 2.5m1 8L21.5 7");
}

.g_9762bos {
  fill: currentColor;
  d: path("M7 11h2.5a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 17v-2.5A3.5 3.5 0 0 1 7 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
