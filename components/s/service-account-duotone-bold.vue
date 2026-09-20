<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b_0ghfb0y"/><path class="mzv5l34he"/><path class="yxnzj4kct"/><path class="wlnjwfbkn"/><path class="jtqt-jkjg"/><path class="ptxh1kbpm"/><path class="avdamgajo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:service-account-duotone-bold" /></template>
<style>
.avdamgajo {
  d: path("M6 21a6 6 0 0 1 12 0");
}

.b_0ghfb0y {
  fill: currentColor;
  d: path("M7 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jtqt-jkjg {
  d: path("M9 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mzv5l34he {
  fill: currentColor;
  d: path("M9 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ptxh1kbpm {
  d: path("M13 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wlnjwfbkn {
  d: path("M7 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.yxnzj4kct {
  fill: currentColor;
  d: path("M13 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
