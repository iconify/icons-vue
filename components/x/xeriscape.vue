<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud8-k0b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:xeriscape" /></template>
<style>
.ud8-k0b8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h19m-13 0v-15a2 2 0 0 1 4 0v15m-4-6h-3V10m7 2h3V8m0 12.5c0-3 1.25-4.25 2.75-4.25S21 17.5 21 20.5");
}

</style>
