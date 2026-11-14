<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z60-y8brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:temperature-high-alert" /></template>
<style>
.z60-y8brj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13.5V5.25a2.75 2.75 0 0 1 5.5 0v8.25a4.5 4.5 0 1 1-5.5 0M9 17V5.5m9 9.25v3.5M18 21h.01");
}

</style>
