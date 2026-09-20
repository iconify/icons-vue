<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fkayfqbji"/><path class="s9jzbjbwv"/><path class="mdgkgma6v"/><path class="cvqe-8bsy"/><path class="vhnbtvbtn"/><path class="jyd5g773m"/><path class="d_scobift"/><path class="u-x8-1cug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:relevance-score-duotone-thin" /></template>
<style>
.cvqe-8bsy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h6");
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jyd5g773m {
  d: path("M3 13h12");
}

.mdgkgma6v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s9jzbjbwv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u-x8-1cug {
  d: path("M17 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

</style>
