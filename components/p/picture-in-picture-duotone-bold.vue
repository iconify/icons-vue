<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g7d56fjnv"/><path class="pj0u6v_oe"/><path class="vyks9vbfn"/><path class="dpqj00aol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:picture-in-picture-duotone-bold" /></template>
<style>
.dpqj00aol {
  d: path("M12 14.75a2.25 2.25 0 0 1 2.25 -2.25h2.5A2.25 2.25 0 0 1 19 14.75 2.25 2.25 0 0 1 16.75 17h-2.5A2.25 2.25 0 0 1 12 14.75");
}

.g7d56fjnv {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pj0u6v_oe {
  fill: currentColor;
  d: path("M12 14.75a2.25 2.25 0 0 1 2.25 -2.25h2.5A2.25 2.25 0 0 1 19 14.75 2.25 2.25 0 0 1 16.75 17h-2.5A2.25 2.25 0 0 1 12 14.75");
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

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
