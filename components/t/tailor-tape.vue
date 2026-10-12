<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ix1rbnbtt"/><path class="h6_s9xbbb"/><rect class="r96tk1k6r"/><path class="vk3r73kuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tailor-tape" /></template>
<style>
.h6_s9xbbb {
  d: path("M14.25 8a2.25 2.25 0 1 1-4.5 0a2.25 2.25 0 1 1 4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ix1rbnbtt {
  cx: 12px;
  cy: 8px;
  r: 5.25px;
}

.r96tk1k6r {
  width: 18.5px;
  height: 5.5px;
  x: 2.75px;
  y: 15.75px;
  rx: 1.75px;
}

.vk3r73kuh {
  d: path("M6.5 15.75v2m4-2v2m4-2v2m4-2v2");
}

</style>
