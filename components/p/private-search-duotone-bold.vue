<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g7od41byc"/><path class="t-2znkbva"/><path class="p367mshbv"/><path class="rseiusb3q"/><path class="qfps29t5x"/><path class="krdtue7ah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:private-search-duotone-bold" /></template>
<style>
.g7od41byc {
  fill: currentColor;
  d: path("M5.5 10a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.krdtue7ah {
  d: path("M10.5 9a1.5 1.5 0 0 1 3 0");
}

.p367mshbv {
  d: path("M5.5 10a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

.qfps29t5x {
  d: path("M9 9h6v3H9Z");
}

.rseiusb3q {
  d: path("M16.5 14.5 21 19");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t-2znkbva {
  fill: currentColor;
  d: path("M9 9h6v3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
