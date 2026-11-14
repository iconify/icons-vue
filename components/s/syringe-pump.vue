<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="klq19t3ii"/><path class="dct9awjvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:syringe-pump" /></template>
<style>
.dct9awjvy {
  d: path("M6.5 15.5h3A1.5 1.5 0 0 1 11 17v.5A1.5 1.5 0 0 1 9.5 19h-3A1.5 1.5 0 0 1 5 17.5V17a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klq19t3ii {
  d: path("M6 13h12a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-1.5A3.5 3.5 0 0 1 6 13m.25-7.5h7A1.75 1.75 0 0 1 15 7.25v1A1.75 1.75 0 0 1 13.25 10h-7A1.75 1.75 0 0 1 4.5 8.25v-1A1.75 1.75 0 0 1 6.25 5.5M2.5 7.75h2m10.5 0h4.25m0-2.25V10M7.5 5.5V7M10 5.5V7m-.25 3v3");
}

</style>
