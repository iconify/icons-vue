<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp0qn4-jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wave-choppy" /></template>
<style>
.yp0qn4-jv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 7l3-2.5L9 7l3-2.5L15 7l3-2.5L21 7M3 13l3-2.5L9 13l3-2.5l3 2.5l3-2.5l3 2.5M3 19l3-2.5L9 19l3-2.5l3 2.5l3-2.5l3 2.5");
}

</style>
