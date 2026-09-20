<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hkn75vgei"/><path class="lbl-xgx4l"/><path class="xbaewdsnx"/><path class="lc7bb5w9b"/><path class="e1_au8jbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:photosynthesis-duotone-regular" /></template>
<style>
.e1_au8jbg {
  d: path("m20 9 -3 3");
}

.hkn75vgei {
  fill: currentColor;
  d: path("M6 20c0 -9 5.4 -12.6 12.6 -12.6C18.6 14.6 11.4 20 6 20");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lbl-xgx4l {
  d: path("M6 20c0 -9 5.4 -12.6 12.6 -12.6C18.6 14.6 11.4 20 6 20");
}

.lc7bb5w9b {
  d: path("m20 4 -4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xbaewdsnx {
  d: path("m16 4 -4 4");
}

</style>
