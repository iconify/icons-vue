<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p30fdt7vx"/><path class="wu7f_71pz"/><path class="wzc2u6bcv"/><path class="kvb76bb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-locomotive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvb76bb7q {
  d: path("M19.5 14.5h2v-1.75");
}

.p30fdt7vx {
  d: path("M3 14.75v-9A1.75 1.75 0 0 1 4.75 4h4a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 0 12.25 9h5.5a1.75 1.75 0 0 1 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75h-13A1.75 1.75 0 0 1 3 14.75");
}

.wu7f_71pz {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2 20.5h20");
}

.wzc2u6bcv {
  fill: currentColor;
  d: path("M15.25 12.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
