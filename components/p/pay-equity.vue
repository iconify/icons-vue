<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9wnyebiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pay-equity" /></template>
<style>
.f9wnyebiu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M3.5 7h17M12 7v13.5m-3.5 0h7M5.5 7v6M2 13h7a3.5 3.5 0 0 1-7 0m16.5-6v6M15 13h7a3.5 3.5 0 0 1-7 0");
}

</style>
