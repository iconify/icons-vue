<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxm68chhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:port-ethernet" /></template>
<style>
.mxm68chhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 5h11.5a1.75 1.75 0 0 1 1.75 1.75v7a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 0 16 17.25A1.75 1.75 0 0 1 14.25 19h-4.5A1.75 1.75 0 0 1 8 17.25a1.75 1.75 0 0 0-1.75-1.75a1.75 1.75 0 0 1-1.75-1.75v-7A1.75 1.75 0 0 1 6.25 5M8 8v2.5M10.75 8v2.5m2.5-2.5v2.5M16 8v2.5");
}

</style>
