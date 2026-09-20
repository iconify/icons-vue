<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i211t9xib"/><path class="xfs8wlfhn"/><path class="iml3cbclx"/><path class="mo1bh2_2m"/><path class="zpdz8rbaf"/><path class="s9itk2b_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mass-assignment-duotone-bold" /></template>
<style>
.i211t9xib {
  fill: currentColor;
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iml3cbclx {
  d: path("M8 7a4 4 0 0 1 8 0");
}

.mo1bh2_2m {
  d: path("M9 12.5h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s9itk2b_k {
  d: path("M9 18.5h6");
}

.xfs8wlfhn {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.zpdz8rbaf {
  d: path("M9 15.5h6");
}

</style>
