<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dv3fg41zd"/><path class="f7_9udqlo"/><path class="a85y0t8_i"/><path class="crgm97xoy"/><path class="k4qo1xe9v"/><path class="x4bmljlar"/><path class="wtfq6b2ta"/><path class="ui32hib9b"/><path class="htavkzbpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shuttle-bus-duotone-thin" /></template>
<style>
.a85y0t8_i {
  fill: currentColor;
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.crgm97xoy {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.dv3fg41zd {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f7_9udqlo {
  fill: currentColor;
  d: path("M6 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.htavkzbpk {
  d: path("m17 18 2 2 -2 2");
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.ui32hib9b {
  d: path("M5 20h14");
}

.wtfq6b2ta {
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.x4bmljlar {
  d: path("M6 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
