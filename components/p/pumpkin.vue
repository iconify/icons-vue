<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jovd8z0nb"/><path class="qnr1gfunj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pumpkin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jovd8z0nb {
  d: path("M12 7c-7-.5-9 4-8.5 7.5S7.5 20 12 20s8-2 8.5-5.5S19 6.5 12 7");
}

.qnr1gfunj {
  d: path("M12 7c0-2 .5-3 2-3.5M12 7c-3 3-3 10 0 13m0-13c3 3 3 10 0 13");
}

</style>
