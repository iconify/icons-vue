<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8-7uq5lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-wildlife" /></template>
<style>
.m8-7uq5lb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12c0-1.25 1-2 2.5-2h7L16 6h3.5l1 1.5l-3 2l-1.5 4c-.5 1-1 1.5-2 1.5H6.5C5 15 4 14 4 12m2.5 3L6 21m8-6l.5 6M17 6l-1-3.5m.5 1.75l-2.5-1");
}

</style>
