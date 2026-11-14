<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye4obnb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-luggage-storage" /></template>
<style>
.ye4obnb-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5h5A3.5 3.5 0 0 1 18 9v7a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 16V9a3.5 3.5 0 0 1 3.5-3.5m0 0v-3h5v3M9.5 9v7m5-7v7");
}

</style>
