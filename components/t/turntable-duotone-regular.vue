<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="timnnhbxi"/><path class="xk4s9ccgz"/><path class="no_v-sbjp"/><path class="q6bd2y71t"/><path class="c33zbvbwu"/><path class="xlsprdnsf"/><path class="zni8d8bse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:turntable-duotone-regular" /></template>
<style>
.c33zbvbwu {
  d: path("M4 13a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.no_v-sbjp {
  fill: currentColor;
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q6bd2y71t {
  d: path("M3 5v16h18V5Z");
}

.timnnhbxi {
  fill: currentColor;
  d: path("M3 5v16h18V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xk4s9ccgz {
  fill: currentColor;
  d: path("M4 13a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xlsprdnsf {
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zni8d8bse {
  d: path("m18 8 -4 4");
}

</style>
