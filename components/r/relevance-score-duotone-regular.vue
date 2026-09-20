<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fkayfqbji"/><path class="aqrf9ebcv"/><path class="x-gsg4bzf"/><path class="lf6jf1bxr"/><path class="vhnbtvbtn"/><path class="jyd5g773m"/><path class="d_scobift"/><path class="u-x8-1cug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:relevance-score-duotone-regular" /></template>
<style>
.aqrf9ebcv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d_scobift {
  d: path("M3 18h6");
}

.fkayfqbji {
  fill: currentColor;
  d: path("M17 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jyd5g773m {
  d: path("M3 13h12");
}

.lf6jf1bxr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u-x8-1cug {
  d: path("M17 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.x-gsg4bzf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
