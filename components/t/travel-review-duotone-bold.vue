<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g9o_8l5pu"/><path class="n_odlvb-k"/><path class="z7ca-so4r"/><path class="jfx-5ab5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-review-duotone-bold" /></template>
<style>
.g9o_8l5pu {
  fill: currentColor;
  d: path("M4 4h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2h-7l-5 5v-5H4a2 2 0 0 1 -2 -2V6a2 2 0 0 1 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jfx-5ab5j {
  d: path("m12 8.5 2 2 -2 2 -2 -2Z");
}

.n_odlvb-k {
  fill: currentColor;
  d: path("m12 8.5 2 2 -2 2 -2 -2Z");
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

.z7ca-so4r {
  d: path("M4 4h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2h-7l-5 5v-5H4a2 2 0 0 1 -2 -2V6a2 2 0 0 1 2 -2");
}

</style>
