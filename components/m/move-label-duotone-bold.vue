<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fbde_z08y"/><path class="w3hyiobto"/><path class="w0sebyb3m"/><path class="ue3yoeyrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:move-label-duotone-bold" /></template>
<style>
.fbde_z08y {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ue3yoeyrj {
  d: path("m12.5 11 2.5 2.5 -2.5 2.5");
}

.w0sebyb3m {
  d: path("M9 13.5h6");
}

.w3hyiobto {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

</style>
