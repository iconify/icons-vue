<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx0h0yl2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sawhorse" /></template>
<style>
.cx0h0yl2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5h15A1.5 1.5 0 0 1 21 6.5A1.5 1.5 0 0 1 19.5 8h-15A1.5 1.5 0 0 1 3 6.5A1.5 1.5 0 0 1 4.5 5m2 3L4 21M17.5 8L20 21M5 15h14");
}

</style>
