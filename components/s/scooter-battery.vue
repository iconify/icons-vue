<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xh4b8uwdt"/><path class="h0fgavb6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scooter-battery" /></template>
<style>
.h0fgavb6h {
  d: path("m5.5 17l2-13.5h3m5.25 12h4q1 0 1 1h1v2h-1q0 1-1 1h-4q-1 0-1-1v-2q0-1 1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xh4b8uwdt {
  d: path("M3 17a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m9.352-2.468q-.109.017-.216.044q-.107.028-.211.064t-.204.082t-.197.099t-.187.117q-.091.062-.176.132t-.164.148t-.15.161t-.136.174q-.063.09-.119.185t-.103.195t-.085.203t-.067.21t-.048.215q-.02.109-.029.219t-.01.22q0 .101.008.201t.024.2t.041.197t.056.193t.071.188q.039.093.086.182t.101.175t.114.165q.06.081.127.156q.067.076.14.145q.072.07.15.134t.161.121t.17.107t.178.094t.185.079t.191.064M5.5 17h6.4");
}

</style>
