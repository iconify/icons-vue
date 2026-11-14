<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af5ks7b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mudroom" /></template>
<style>
.af5ks7b_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3h1A1.75 1.75 0 0 1 7.5 4.75v9.789a1.75 1.75 0 0 0 .81 1.477l1.13.718a1.75 1.75 0 0 1 .81 1.477v1.539A1.75 1.75 0 0 1 8.5 21.5H4.75A1.75 1.75 0 0 1 3 19.75v-15A1.75 1.75 0 0 1 4.75 3m10 0h1a1.75 1.75 0 0 1 1.75 1.75v9.789a1.75 1.75 0 0 0 .81 1.477l1.13.718a1.75 1.75 0 0 1 .81 1.477v1.539a1.75 1.75 0 0 1-1.75 1.75h-3.75A1.75 1.75 0 0 1 13 19.75v-15A1.75 1.75 0 0 1 14.75 3M3 6.5h4.5m5.5 0h4.5");
}

</style>
