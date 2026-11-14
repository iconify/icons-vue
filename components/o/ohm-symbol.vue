<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2sh1fqsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ohm-symbol" /></template>
<style>
.w2sh1fqsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14h4v-1.5a5.25 5.25 0 1 1 6 0V14h4M2.5 19.25h3.25L7 17.5L9.5 21l2.5-3.5l2.5 3.5l2.5-3.5l1.25 1.75h3.25");
}

</style>
