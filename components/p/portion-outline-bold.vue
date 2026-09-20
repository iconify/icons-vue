<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mqtixbwqo"/><path class="bso0bbbqi"/><path class="z8g2jgblp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:portion-outline-bold" /></template>
<style>
.bso0bbbqi {
  d: path("M21 8A9 9 0 0 1 3 8");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z8g2jgblp {
  d: path("M5 12h14");
}

</style>
