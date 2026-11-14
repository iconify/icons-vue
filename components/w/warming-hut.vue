<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sda11sb4z"/><path class="bxd4lcl0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warming-hut" /></template>
<style>
.bxd4lcl0u {
  d: path("M11.25 14.5h1.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 12.75 19h-1.5a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sda11sb4z {
  d: path("m5.05 12.213l5.375-4.032a2.625 2.625 0 0 1 3.15 0l5.375 4.032a2.63 2.63 0 0 1 1.05 2.1v4.562a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875v-4.562a2.63 2.63 0 0 1 1.05-2.1M16 10V6.5h3v5.75m-1.5-8.5c1-1.25 2.5.75 4-.75");
}

</style>
