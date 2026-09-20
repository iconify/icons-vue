<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zc7-aybrt"/><path class="mxah8kvgx"/><path class="o5r_prbgx"/><path class="ai0e6e9tr"/><path class="da8_tjeku"/><path class="woyykhguz"/><path class="wpz4ckbwy"/><path class="fy2_4cbcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:route-alt-duotone-bold" /></template>
<style>
.ai0e6e9tr {
  d: path("M16 19a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.da8_tjeku {
  d: path("M5 9v7h11v3");
}

.fy2_4cbcf {
  d: path("M19 11v4");
}

.mxah8kvgx {
  fill: currentColor;
  d: path("M16 19a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o5r_prbgx {
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.woyykhguz {
  d: path("M9 5h3.5");
}

.wpz4ckbwy {
  d: path("M15.5 5H19v3");
}

.zc7-aybrt {
  fill: currentColor;
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
