<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w5m7kgb8g"/><path class="q_z3ldx1l"/><path class="iev78-4aw"/><path class="ifmxbfbzl"/><path class="eo0o7bbpy"/><path class="j7cy7sb_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:patio-duotone-bold" /></template>
<style>
.eo0o7bbpy {
  d: path("M14 6h7v5h-7Z");
}

.iev78-4aw {
  fill: currentColor;
  d: path("M3 14h18v5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ifmxbfbzl {
  d: path("M3 6h8v5H3Z");
}

.j7cy7sb_r {
  d: path("M3 14h18v5H3Z");
}

.q_z3ldx1l {
  fill: currentColor;
  d: path("M14 6h7v5h-7Z");
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

.w5m7kgb8g {
  fill: currentColor;
  d: path("M3 6h8v5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
