<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v9hkdub2y"/><path class="bmpn0zqcr"/><path class="qcttaobtu"/><path class="hvc_kfbbh"/><path class="fipykcbwt"/><path class="d210vyb8t"/><path class="ig2rw3qjx"/><path class="hs_3awbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shuffle-duotone-bold" /></template>
<style>
.bmpn0zqcr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 13 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d210vyb8t {
  d: path("m18 13 3 3 -3 3");
}

.fipykcbwt {
  d: path("M3 7h6l9 9h3");
}

.hs_3awbse {
  d: path("m18 5 3 3 -3 3");
}

.hvc_kfbbh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ig2rw3qjx {
  d: path("M3 17h6l9 -9h3");
}

.qcttaobtu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h6l9 -9h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v9hkdub2y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h6l9 9h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
