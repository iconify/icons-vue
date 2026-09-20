<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wuq55s4_w"/><path class="ga97lpb2d"/><path class="hd5x_f8cb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:threat-event-duotone-bold" /></template>
<style>
.ga97lpb2d {
  d: path("M3 5h9v6l-4.5 4.5L3 11Z");
}

.hd5x_f8cb {
  d: path("m21 7 -4 4h3l-4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wuq55s4_w {
  fill: currentColor;
  d: path("M3 5h9v6l-4.5 4.5L3 11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
