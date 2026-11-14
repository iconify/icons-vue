<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9_3k3z3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:selection-subtract" /></template>
<style>
.z9_3k3z3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5V5h3M10 5h4m3.5 0h3v2.5m0 3v3m0 3V19h-3M14 19h-4m-3.5 0h-3v-2.5m0-6v3m5-1.5h7");
}

</style>
