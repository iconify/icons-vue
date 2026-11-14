<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt751-jus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pulley-block" /></template>
<style>
.vt751-jus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h6m-3 0V4M6 9a5 5 0 1 0 10 0A5 5 0 1 0 6 9m0 0v12.5M16 9v6.5M11 9h.01m3.74 6.5h2.5A1.75 1.75 0 0 1 19 17.25v2A1.75 1.75 0 0 1 17.25 21h-2.5A1.75 1.75 0 0 1 13 19.25v-2a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
