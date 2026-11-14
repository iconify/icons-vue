<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuw4ebbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:transfer-reverse" /></template>
<style>
.vuw4ebbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 6H7m3.5-3.5L7 6l3.5 3.5M4 12h13m-3.5-3.5L17 12l-3.5 3.5M21 18h-6m2.5-2.5L15 18l2.5 2.5");
}

</style>
