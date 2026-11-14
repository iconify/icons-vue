<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-zirabqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset-alert" /></template>
<style>
.t-zirabqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5h13A2.5 2.5 0 0 1 21 6v2.5a2.5 2.5 0 0 1-2.5 2.5H15a3 3 0 0 0-6 0H5.5A2.5 2.5 0 0 1 3 8.5V6a2.5 2.5 0 0 1 2.5-2.5m13.833 12.833l1.538 2.979a1.5 1.5 0 0 1-1.333 2.188h-3.076a1.5 1.5 0 0 1-1.333-2.188l1.538-2.979a1.5 1.5 0 0 1 2.666 0M18 16.75v1.5M18 20h.01");
}

</style>
