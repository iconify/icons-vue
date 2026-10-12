<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ax6tkry-g"/><rect class="eeop_reou"/><path class="adfuznekr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:serum-dropper" /></template>
<style>
.adfuznekr {
  d: path("M12 15c.9 1.1 1.4 1.8 1.4 2.5a1.4 1.4 0 0 1-2.8 0c0-.7.5-1.4 1.4-2.5");
}

.ax6tkry-g {
  d: path("M8.75 10.5h6.5v-2H14V4.75a2 2 0 0 0-4 0V8.5H8.75Z");
}

.eeop_reou {
  width: 12.5px;
  height: 7.75px;
  x: 5.75px;
  y: 13.5px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
