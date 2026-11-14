<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2par6brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:off-camera-flash" /></template>
<style>
.j2par6brj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 9.5h4.75A2.625 2.625 0 0 1 13 12.125v.75a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 3 12.875v-.75A2.625 2.625 0 0 1 5.625 9.5m-.125 6V20A1.5 1.5 0 0 0 7 21.5h2.5A1.5 1.5 0 0 0 11 20v-4.5m2.906-9.381a3.5 3.5 0 0 1 2.475 2.475m-1.569-5.855a7 7 0 0 1 4.949 4.949");
}

</style>
