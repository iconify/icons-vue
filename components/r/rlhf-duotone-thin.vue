<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tzdfp4-do"/><path class="ufzn_r3vk"/><path class="kb4snmb2s"/><path class="zllo9xxih"/><path class="lf7-wkbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rlhf-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kb4snmb2s {
  d: path("M6.5 19a5.5 5.5 0 0 1 11 0");
}

.lf7-wkbzn {
  d: path("M17 3.34a10 10 0 0 1 0 17.32");
}

.tzdfp4-do {
  fill: currentColor;
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ufzn_r3vk {
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.zllo9xxih {
  d: path("M7 20.66A10 10 0 0 1 7 3.34");
}

</style>
