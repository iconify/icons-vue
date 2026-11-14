<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iblzp2ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:workflow-dispatch" /></template>
<style>
.iblzp2ble {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 2.5h1.75A2.625 2.625 0 0 1 9.5 5.125v1.75A2.625 2.625 0 0 1 6.875 9.5h-1.75A2.625 2.625 0 0 1 2.5 6.875v-1.75A2.625 2.625 0 0 1 5.125 2.5M14 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-8.875 8.5h1.75A2.625 2.625 0 0 1 9.5 17.125v1.75A2.625 2.625 0 0 1 6.875 21.5h-1.75A2.625 2.625 0 0 1 2.5 18.875v-1.75A2.625 2.625 0 0 1 5.125 14.5M9.5 6H14M6 9.5v5m11.135.545l2.04 1.195a1.75 1.75 0 0 1 0 3.02l-2.04 1.195a1.75 1.75 0 0 1-2.635-1.509v-2.392a1.75 1.75 0 0 1 2.635-1.509");
}

</style>
