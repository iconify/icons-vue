<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y830gbwbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:same-store-sales" /></template>
<style>
.y830gbwbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M7.5 15H9a1.5 1.5 0 0 1 1.5 1.5V20A1.5 1.5 0 0 1 9 21.5H7.5A1.5 1.5 0 0 1 6 20v-3.5A1.5 1.5 0 0 1 7.5 15m7.5-3.5h1.5A1.5 1.5 0 0 1 18 13v7a1.5 1.5 0 0 1-1.5 1.5H15a1.5 1.5 0 0 1-1.5-1.5v-7a1.5 1.5 0 0 1 1.5-1.5m-12 10h18");
}

</style>
