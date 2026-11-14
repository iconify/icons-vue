<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-94s4bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wake-up" /></template>
<style>
.c-94s4bsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18h18M7 18a5 5 0 0 1 10 0M12 2.5V9M9.5 5L12 2.5L14.5 5M4 10.5l1.25 1.25M20 10.5l-1.25 1.25M8 21.25h8");
}

</style>
