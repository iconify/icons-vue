<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fyop2-bcy"/><path class="ay577bo1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:premium-paid" /></template>
<style>
.ay577bo1x {
  d: path("M12.75 8.75C12.5 8 11.9 7.5 11 7.5c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M11 6.25V7.5m0 6v1.25M14.75 18l2 2L21 15.75");
}

.fyop2-bcy {
  d: path("M19.5 12.25a8.5 8.5 0 1 0-7.25 7.25a6 6 0 0 1 7.25-7.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
