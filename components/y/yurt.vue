<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3dok_bhf"/><rect class="gvi_rryiy"/><path class="xdavuwbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yurt" /></template>
<style>
.gvi_rryiy {
  width: 16.5px;
  height: 8px;
  x: 3.75px;
  y: 13.25px;
  rx: 0.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3dok_bhf {
  d: path("M2.75 13.25C5.5 10 8.5 7.5 12 6.25c3.5 1.25 6.5 3.75 9.25 7Zm9.25-7V3");
}

.xdavuwbps {
  d: path("M3.75 16H8.5m7 0h4.75m-9.75 5.25v-4.5h3v4.5");
}

</style>
