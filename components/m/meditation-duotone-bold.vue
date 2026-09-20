<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oe3oa5b3b"/><path class="lox4axb5m"/><path class="w08657bnd"/><path class="tai76ebzb"/><path class="uto0n9pso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:meditation-duotone-bold" /></template>
<style>
.lox4axb5m {
  fill: currentColor;
  d: path("m4 19 8 -8 8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oe3oa5b3b {
  fill: currentColor;
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

.tai76ebzb {
  d: path("m4 19 8 -8 8 8Z");
}

.uto0n9pso {
  d: path("M7 16h10");
}

.w08657bnd {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
