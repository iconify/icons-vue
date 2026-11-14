<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nvdugdc6o"/><path class="prmv6_0xb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treehouse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nvdugdc6o {
  d: path("m7.939 8.561l3-3a1.5 1.5 0 0 1 2.122 0l3 3a1.5 1.5 0 0 1 .439 1.06V12.5A1.5 1.5 0 0 1 15 14H9a1.5 1.5 0 0 1-1.5-1.5V9.621a1.5 1.5 0 0 1 .439-1.06M5.5 14h13m-9 0v7.5M6 14L3 9m15 5l3-5");
}

.prmv6_0xb {
  d: path("M11 14v-3h2v3m-.25 0v7.5m3-7.5v7.5m-3-4.75h3m-3 2.5h3");
}

</style>
