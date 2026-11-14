<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7px_8bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:promo-countdown-timer" /></template>
<style>
.k7px_8bbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5H13m-9.5 17h9.1m-8.1-17V5c0 3.5 3.75 4.5 3.75 6S4.5 13.5 4.5 17v2.5m7.5-17V5c0 3.5-3.75 4.5-3.75 6S12 13.5 12 17v2.5m2.75 1.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
