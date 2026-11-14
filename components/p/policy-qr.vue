<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blntpgbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:policy-qr" /></template>
<style>
.blntpgbzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2M9 7.5h.5A1.5 1.5 0 0 1 11 9v.5A1.5 1.5 0 0 1 9.5 11H9a1.5 1.5 0 0 1-1.5-1.5V9A1.5 1.5 0 0 1 9 7.5m5.5 0h.5A1.5 1.5 0 0 1 16.5 9v.5A1.5 1.5 0 0 1 15 11h-.5A1.5 1.5 0 0 1 13 9.5V9a1.5 1.5 0 0 1 1.5-1.5M9 13h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 15v-.5A1.5 1.5 0 0 1 9 13m5.75 1.75h.01m1.74 1.75h.01");
}

</style>
