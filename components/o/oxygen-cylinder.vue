<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="weeyhebtc"/><circle class="p2g73nubi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oxygen-cylinder" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p2g73nubi {
  cx: 16.75px;
  cy: 6px;
  r: 2.25px;
}

.weeyhebtc {
  d: path("M8.5 9.05V5.5a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v3.55a2.5 2.5 0 0 1 2 2.45V19a1.5 1.5 0 0 1-1.5 1.5H8A1.5 1.5 0 0 1 6.5 19v-7.5a2.5 2.5 0 0 1 2-2.45M6.5 14h7m-5-8h-3m6 0h3");
}

</style>
