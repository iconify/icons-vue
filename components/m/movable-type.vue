<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txs6-ublb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:movable-type" /></template>
<style>
.txs6-ublb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5h7A3.5 3.5 0 0 1 19 7v7a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 14V7a3.5 3.5 0 0 1 3.5-3.5M3 20.5h18M8.5 7.5h7m-3.5 0V14");
}

</style>
