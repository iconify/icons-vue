<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="j5kk_9bzl"/><circle class="x9trnnban"/><path class="t7fp-nbec"/><circle class="htjvm_qjp"/><path class="iu8qwg6tc"/><circle class="wgxxv3bzs"/><path class="p6js_ybfk"/><g class="umm606kxf"><path class="dfssf787j"/><path class="wn-g5bevx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:three-thirty" /></template>
<style>
.dfssf787j {
  stroke: var(--svg-color--6596a3, #6596a3);
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M64 100v5m0-82v5m0 72v5m0-82v5M28 64h-5m82 0h-5m-72 0h-5m82 0h-5");
}

.htjvm_qjp {
  cx: 64px;
  cy: 64px;
  r: 45.59px;
  fill: var(--svg-color--fff, #fff);
}

.iu8qwg6tc {
  fill: none;
  stroke: var(--svg-color--563428, #563428);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4px, 4px);
  d: path("M64 64v29");
}

.j5kk_9bzl {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--98c0d0, #98c0d0);
}

.p6js_ybfk {
  fill: none;
  stroke: var(--svg-color--563428, #563428);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--6px, 6px);
  d: path("M84.84 69.35L64.29 64");
}

.t7fp-nbec {
  fill: var(--svg-color--c2e3f0, #c2e3f0);
  d: path("M50.3 15.06c-6.42 1.86-15.41 4.71-25.03 16.2c-9.5 11.37-11.46 24.58-12.07 33.69c0 0-5.49 6.87-5.75 5.59c-2.07-9.95 2.11-32.19 13.04-43.95C33.21 12.91 49.75 8.06 55.73 7.15c1.03-.16-3.48 7.35-5.43 7.91");
}

.umm606kxf {
  fill: none;
  stroke-miterlimit: 10;
}

.wgxxv3bzs {
  cx: 64px;
  cy: 64px;
  r: 5.06px;
  fill: var(--svg-color--563428, #563428);
}

.wn-g5bevx {
  stroke: var(--svg-color--b0bec5, #b0bec5);
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("m46 95.18l-2.5 4.33m41-71.02L82 32.82M46 95.18l-2.5 4.33m41-71.02L82 32.82m0 62.36l2.5 4.33m-41-71.02l2.5 4.33m36 62.36l2.5 4.33m-41-71.02l2.5 4.33M95.18 82l4.33 2.5m-71.02-41l4.33 2.5m62.36 36l4.33 2.5m-71.02-41l4.33 2.5m0 36l-4.33 2.5m71.02-41L95.18 46M32.82 82l-4.33 2.5m71.02-41L95.18 46");
}

.x9trnnban {
  cx: 64px;
  cy: 64px;
  r: 48.14px;
  fill: var(--svg-color--fcebcd, #fcebcd);
}

</style>
