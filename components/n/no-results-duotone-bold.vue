<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hqafrt8gv"/><path class="aai5cvb0q"/><path class="g69nh1q2b"/><path class="x6kbyg_lb"/><path class="ury5s7a4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:no-results-duotone-bold" /></template>
<style>
.aai5cvb0q {
  d: path("M4 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.g69nh1q2b {
  d: path("m5.5 13.5 -3 3");
}

.hqafrt8gv {
  fill: currentColor;
  d: path("M4 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
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

.ury5s7a4p {
  d: path("m22 12 -5 5");
}

.x6kbyg_lb {
  d: path("m17 12 5 5");
}

</style>
