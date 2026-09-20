<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pexaq3klw"/><path class="yqql_ccjj"/><path class="n38ia2-4t"/><path class="x51hl3b-b"/><path class="z_si_bbvo"/><path class="fp43k-buc"/><path class="i2-ny_bzf"/><path class="zm2dyvb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:robo-advisor-duotone-bold" /></template>
<style>
.fp43k-buc {
  d: path("M14 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.n38ia2-4t {
  fill: currentColor;
  d: path("M14 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pexaq3klw {
  fill: currentColor;
  d: path("M4 9a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
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

.x51hl3b-b {
  d: path("M4 9a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.yqql_ccjj {
  fill: currentColor;
  d: path("M8 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z_si_bbvo {
  d: path("M8 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zm2dyvb-o {
  d: path("M9 16h6");
}

</style>
