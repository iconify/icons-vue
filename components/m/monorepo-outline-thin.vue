<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xhii43btc"/><path class="vslz5yb3q"/><path class="qooj3fbsi"/><path class="zn_a46_dj"/><path class="bdzqutb3d"/><path class="gn7q9ebir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:monorepo-outline-thin" /></template>
<style>
.bdzqutb3d {
  d: path("M2 17a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.gn7q9ebir {
  d: path("M14 17a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qooj3fbsi {
  d: path("M6 12v3");
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.xhii43btc {
  d: path("M8 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.zn_a46_dj {
  d: path("M18 12v3");
}

</style>
