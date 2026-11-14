<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q32btkb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:surf-booties" /></template>
<style>
.q32btkb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h3.5A1.5 1.5 0 0 1 9 5v.5A1.5 1.5 0 0 1 7.5 7H4a1.5 1.5 0 0 1-1.5-1.5V5A1.5 1.5 0 0 1 4 3.5M3 7v11.5A1.5 1.5 0 0 0 4.5 20h4a2 2 0 0 0 2-2c0-2-2-2.5-2-5V7M15 3.5h3.5A1.5 1.5 0 0 1 20 5v.5A1.5 1.5 0 0 1 18.5 7H15a1.5 1.5 0 0 1-1.5-1.5V5A1.5 1.5 0 0 1 15 3.5M14 7v11.5a1.5 1.5 0 0 0 1.5 1.5h4a2 2 0 0 0 2-2c0-2-2-2.5-2-5V7");
}

</style>
