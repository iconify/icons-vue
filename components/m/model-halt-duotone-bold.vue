<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w2ed1xbxm"/><path class="bfp2j21qb"/><path class="p39ktbcba"/><path class="oowiv7bzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-halt-duotone-bold" /></template>
<style>
.bfp2j21qb {
  fill: currentColor;
  d: path("M14 8h8v8h-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oowiv7bzr {
  d: path("M14 8h8v8h-8Z");
}

.p39ktbcba {
  d: path("m7 8 4 4 -4 4 -4 -4Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w2ed1xbxm {
  fill: currentColor;
  d: path("m7 8 4 4 -4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
