<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fbde_z08y"/><path class="o1bec9b2h"/><path class="w3hyiobto"/><path class="vw_dl18nv"/><path class="da_3coiun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tag-alert-duotone-bold" /></template>
<style>
.da_3coiun {
  d: path("M11 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.fbde_z08y {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o1bec9b2h {
  fill: currentColor;
  d: path("M11 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.vw_dl18nv {
  d: path("M12 10.5v3");
}

.w3hyiobto {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

</style>
