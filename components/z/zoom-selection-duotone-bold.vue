<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o0gte2bxq"/><path class="i-gfgd81w"/><path class="fi55a390y"/><path class="jq4q_eqbj"/><path class="s5cpnzbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:zoom-selection-duotone-bold" /></template>
<style>
.fi55a390y {
  d: path("M3 11a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.i-gfgd81w {
  fill: currentColor;
  d: path("M7.5 9.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jq4q_eqbj {
  d: path("M7.5 9.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.o0gte2bxq {
  fill: currentColor;
  d: path("M3 11a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
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

.s5cpnzbno {
  d: path("M16.5 16.5 21 21");
}

</style>
