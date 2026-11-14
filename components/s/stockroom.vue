<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ybslbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stockroom" /></template>
<style>
.k1ybslbtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19m18-19v19M3 9h18M3 15.5h18m-18 6h18M7 3.5h3A1.5 1.5 0 0 1 11.5 5v2.5A1.5 1.5 0 0 1 10 9H7a1.5 1.5 0 0 1-1.5-1.5V5A1.5 1.5 0 0 1 7 3.5m7.5 2H17A1.5 1.5 0 0 1 18.5 7v.5A1.5 1.5 0 0 1 17 9h-2.5A1.5 1.5 0 0 1 13 7.5V7a1.5 1.5 0 0 1 1.5-1.5m-7.5 6h2a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 9 15.5H7A1.5 1.5 0 0 1 5.5 14v-1A1.5 1.5 0 0 1 7 11.5m7-1h3a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5m-5.5 7h7A1.5 1.5 0 0 1 17 19v1a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 20v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
