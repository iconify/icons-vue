<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfiqo0bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:multi-cursor" /></template>
<style>
.rfiqo0bid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5c1.25 0 2 .5 2 1.75v7.5c0 1.25-.75 1.75-2 1.75m4-11c-1.25 0-2 .5-2 1.75m2 9.25c-1.25 0-2-.5-2-1.75m5-1.25c1.25 0 2 .5 2 1.75v7.5c0 1.25-.75 1.75-2 1.75m4-11c-1.25 0-2 .5-2 1.75m2 9.25c-1.25 0-2-.5-2-1.75");
}

</style>
