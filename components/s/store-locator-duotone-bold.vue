<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z1ra8bb5p"/><path class="z6qs6gbnt"/><path class="fmbgtccaf"/><path class="d84te0b3b"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="u7m7z6ojw"/><path class="mqi2_ac9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:store-locator-duotone-bold" /></template>
<style>
.d84te0b3b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 15.5 12 18l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fmbgtccaf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mqi2_ac9e {
  d: path("M9.5 15.5 12 18l2.5 -2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tp7101bon {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

.u7m7z6ojw {
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.yb0d-pkkp {
  d: path("M4 8v14h16V8");
}

.z1ra8bb5p {
  fill: currentColor;
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z6qs6gbnt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
