<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k_2z93bzc"/><path class="qwru3vbrx"/><path class="wkikn6b0e"/><path class="tcenmsthl"/><path class="uls5d7bvt"/><path class="n3p0zmbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:view-duotone-bold" /></template>
<style>
.k_2z93bzc {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n3p0zmbop {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qwru3vbrx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 12 6 -6h6l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tcenmsthl {
  d: path("m3 12 6 -6h6l6 6");
}

.uls5d7bvt {
  d: path("m3 12 6 6h6l6 -6");
}

.wkikn6b0e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 12 6 6h6l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
