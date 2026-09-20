<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ycktj7b1l"/><path class="cvr9mcbfs"/><path class="goos2dscq"/><path class="brgn0dkyh"/><path class="h7k_twb0c"/><path class="lhz2jzbtp"/><path class="m_rvj96ky"/><path class="hi4ej1pvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vote-quorum-duotone-thin" /></template>
<style>
.brgn0dkyh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 11 2 2L15 9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cvr9mcbfs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.goos2dscq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7k_twb0c {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

.hi4ej1pvu {
  d: path("m9.5 11 2 2L15 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhz2jzbtp {
  d: path("M19.27 3.28a3 3 0 1 1 -2.54 0");
}

.m_rvj96ky {
  d: path("M13.27 15.28a3 3 0 1 1 -2.54 0");
}

.ycktj7b1l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
