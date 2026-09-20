<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g7esaduey"/><path class="bkrxi4g3s"/><path class="k-sgg11ok"/><path class="bwxeoibzi"/><path class="x1_r36phd"/><path class="ct75s-bnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:migrate-duotone-thin" /></template>
<style>
.bkrxi4g3s {
  fill: currentColor;
  d: path("M15 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.bwxeoibzi {
  d: path("M15 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.ct75s-bnk {
  d: path("m12 9 3 3 -3 3");
}

.g7esaduey {
  fill: currentColor;
  d: path("M2 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-sgg11ok {
  d: path("M2 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.x1_r36phd {
  d: path("M9 12h6");
}

</style>
