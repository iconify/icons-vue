<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx7wd4b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tuning-a440" /></template>
<style>
.bx7wd4b_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5V10a3.5 3.5 0 0 0 7 0V2.5m-3.5 11v8m6.367-17.008a3.5 3.5 0 0 1 0 4.016m2.867-6.023a7 7 0 0 1 0 8.03");
}

</style>
