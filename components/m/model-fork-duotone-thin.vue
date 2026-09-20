<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tp0cwsbhc"/><path class="tjd3mmylb"/><path class="reuou3bbc"/><path class="qz_by4b2x"/><path class="gc9dmfy3u"/><path class="zzazs-rvi"/><path class="ll_i_4bra"/><path class="ud-rllqqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-fork-duotone-thin" /></template>
<style>
.gc9dmfy3u {
  d: path("m10.5 7.5 -5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ll_i_4bra {
  d: path("M2.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qz_by4b2x {
  d: path("m12 4 2.5 2.5L12 9 9.5 6.5Z");
}

.reuou3bbc {
  fill: currentColor;
  d: path("M17.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tjd3mmylb {
  fill: currentColor;
  d: path("M2.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tp0cwsbhc {
  fill: currentColor;
  d: path("m12 4 2.5 2.5L12 9 9.5 6.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ud-rllqqn {
  d: path("M17.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zzazs-rvi {
  d: path("m13.5 7.5 5 5");
}

</style>
