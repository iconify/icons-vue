<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="euejzbbec"/><path class="epf01ribx"/><path class="stv7yz1mi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:watch-display-pillow" /></template>
<style>
.epf01ribx {
  fill: currentColor;
  d: path("M11.125 2.5h1.75a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-1.75A1.375 1.375 0 0 1 9.75 3.875A1.375 1.375 0 0 1 11.125 2.5m0 11.75h1.75a1.375 1.375 0 0 1 1.375 1.375A1.375 1.375 0 0 1 12.875 17h-1.75a1.375 1.375 0 0 1-1.375-1.375a1.375 1.375 0 0 1 1.375-1.375");
}

.euejzbbec {
  d: path("M8 9.75a4 4 0 1 0 8 0a4 4 0 1 0-8 0M4.75 18h14.5A1.75 1.75 0 0 1 21 19.75a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 19.75A1.75 1.75 0 0 1 4.75 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.stv7yz1mi {
  d: path("M12 7.75v2l1.5 1");
}

</style>
