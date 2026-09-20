<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yn64c1dsb"/><path class="i4x21rbnl"/><path class="tkn_9lu9q"/><path class="q518x4bkb"/><path class="kkikm4b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:minibar-duotone-bold" /></template>
<style>
.i4x21rbnl {
  fill: currentColor;
  d: path("M9.5 13.5v5h5v-5L12 11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kkikm4b5o {
  d: path("M9.5 13.5v5h5v-5L12 11Z");
}

.q518x4bkb {
  d: path("M5 9h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tkn_9lu9q {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.yn64c1dsb {
  fill: currentColor;
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
