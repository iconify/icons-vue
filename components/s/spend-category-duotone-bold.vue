<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g7d56fjnv"/><path class="rc9x_d4xl"/><path class="vyks9vbfn"/><path class="ogtwkzbca"/><path class="x97gz5ilw"/><path class="jxjonebqo"/><path class="hljhthw1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spend-category-duotone-bold" /></template>
<style>
.g7d56fjnv {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hljhthw1y {
  d: path("M8.5 12h3");
}

.jxjonebqo {
  d: path("M8.5 9v3");
}

.ogtwkzbca {
  d: path("M22 9.5h-7v5h7");
}

.rc9x_d4xl {
  fill: currentColor;
  d: path("M5.5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

.x97gz5ilw {
  d: path("M5.5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
