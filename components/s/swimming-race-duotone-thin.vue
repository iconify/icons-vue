<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o0u5m7z1w"/><path class="jja1g7szl"/><path class="llyenq9iw"/><path class="pnt-559_r"/><path class="g_eatebwd"/><path class="prj9u5frn"/><path class="neof5acyb"/><path class="jg5yyubai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swimming-race-duotone-thin" /></template>
<style>
.g_eatebwd {
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg5yyubai {
  d: path("M3 16c3 -2 6 2 9 0s6 2 9 0");
}

.jja1g7szl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 10h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.llyenq9iw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 10 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.neof5acyb {
  d: path("m14 10 4 -4");
}

.o0u5m7z1w {
  fill: currentColor;
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pnt-559_r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16c3 -2 6 2 9 0s6 2 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.prj9u5frn {
  d: path("M9 10h5");
}

</style>
