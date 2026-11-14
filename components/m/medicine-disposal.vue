<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsfcpsbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medicine-disposal" /></template>
<style>
.rsfcpsbko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12L7 21.5h10l1.5-9.5M4 12h16M9.25 2.5za2.25 2.25 0 0 1 2.25 2.25v3A2.25 2.25 0 0 1 9.25 10A2.25 2.25 0 0 1 7 7.75v-3A2.25 2.25 0 0 1 9.25 2.5M7 6.25h4.5M17 3v6m-2.5-2.5L17 9l2.5-2.5");
}

</style>
