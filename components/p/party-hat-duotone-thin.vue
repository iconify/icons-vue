<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b2lcxzbpm"/><path class="eff5yibna"/><path class="uhfv81bjt"/><path class="pq9ly31-r"/><path class="szshe-6ah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:party-hat-duotone-thin" /></template>
<style>
.b2lcxzbpm {
  fill: currentColor;
  d: path("M5 20c2 -6 5 -10 7 -14 2 4 5 8 7 14Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.szshe-6ah {
  d: path("M7 17h10");
}

.uhfv81bjt {
  d: path("M5 20c2 -6 5 -10 7 -14 2 4 5 8 7 14Z");
}

</style>
