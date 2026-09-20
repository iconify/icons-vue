<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h-g3lgb-r"/><path class="guoi_acnp"/><path class="gt1864neo"/><path class="m68-9jb2y"/><path class="g-g6w6buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wild-fish-duotone-thin" /></template>
<style>
.g-g6w6buq {
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gt1864neo {
  d: path("M4 13a8 5 0 0 1 14 0 8 5 0 0 1 -14 0");
}

.guoi_acnp {
  fill: currentColor;
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h-g3lgb-r {
  fill: currentColor;
  d: path("M4 13a8 5 0 0 1 14 0 8 5 0 0 1 -14 0");
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

.m68-9jb2y {
  d: path("m17 9 4 4 -4 4");
}

</style>
