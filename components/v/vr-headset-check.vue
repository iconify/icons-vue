<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esqy5ebvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset-check" /></template>
<style>
.esqy5ebvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h14a2.5 2.5 0 0 1 2.5 2.5v5A2.5 2.5 0 0 1 19 13h-3.75a3.25 3.25 0 0 0-6.5 0H5a2.5 2.5 0 0 1-2.5-2.5v-5A2.5 2.5 0 0 1 5 3m9.75 15l2 2L21 15.75");
}

</style>
