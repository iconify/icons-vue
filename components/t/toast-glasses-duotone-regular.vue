<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e9ua75oit"/><path class="yigzqbc3l"/><path class="bkrf_w1xg"/><path class="gzh4n16ws"/><path class="o46_3ibvz"/><path class="x3kckjo0r"/><path class="xdr0x0btg"/><path class="zgtflacns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toast-glasses-duotone-regular" /></template>
<style>
.bkrf_w1xg {
  d: path("M3 4h6.5c0 4 -1.5 6 -2 8H5c-0.5 -2 -2 -4 -2 -8");
}

.e9ua75oit {
  fill: currentColor;
  d: path("M3 4h6.5c0 4 -1.5 6 -2 8H5c-0.5 -2 -2 -4 -2 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gzh4n16ws {
  d: path("M6 12v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o46_3ibvz {
  d: path("M3 20h6");
}

.x3kckjo0r {
  d: path("M14.5 4H21c0 4 -1.5 6 -2 8h-2.5c-0.5 -2 -2 -4 -2 -8");
}

.xdr0x0btg {
  d: path("M18 12v8");
}

.yigzqbc3l {
  fill: currentColor;
  d: path("M14.5 4H21c0 4 -1.5 6 -2 8h-2.5c-0.5 -2 -2 -4 -2 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zgtflacns {
  d: path("M15 20h6");
}

</style>
