<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibs6lbcto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-guides" /></template>
<style>
.ibs6lbcto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7h7m2.75 0H15m2.75 0h3.75M7 2.5v7m0 2.75V15m0 2.75v3.75M13.5 10H18a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-4.5A3.5 3.5 0 0 1 10 18v-4.5a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
