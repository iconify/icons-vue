<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pwu4s18nq"/><circle class="vn5ttkwgv"/><path class="p3g8tgbqf"/><path class="bm_0h2sol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mouse-animal" /></template>
<style>
.bm_0h2sol {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 16.25c1.75.5 2.75 1.75 2.75 3.5");
}

.p3g8tgbqf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 13.5h.01");
}

.pwu4s18nq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 15.5C4.75 12 8 9.5 12 9.5s6.75 2.75 6.75 5.75c0 1.75-1.25 3-3 3H5c-1.25 0-2.25-1.5-1.75-2.75");
}

.vn5ttkwgv {
  cx: 10.5px;
  cy: 8.75px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
