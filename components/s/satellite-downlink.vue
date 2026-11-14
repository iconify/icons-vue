<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqst8wyjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:satellite-downlink" /></template>
<style>
.rqst8wyjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 3h.5A1.75 1.75 0 0 1 14 4.75v3.5A1.75 1.75 0 0 1 12.25 10h-.5A1.75 1.75 0 0 1 10 8.25v-3.5A1.75 1.75 0 0 1 11.75 3M2.5 4.5H7v4H2.5Zm14.5 0h4.5v4H17Zm-10 2h3m4 0h3m-2.525 5.975a3.5 3.5 0 0 1-4.95 0m3.707 3.907q-.501.097-1.012.114q-.51.018-1.016-.045q-.507-.063-.998-.203q-.49-.141-.953-.357M18 14.5v7m-3-3l3 3l3-3");
}

</style>
