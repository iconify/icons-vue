<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k86txfbxx"/><path class="r4q7pxbjl"/><path class="mnh2g9b1h"/><path class="vvtjq3jew"/><path class="gg9qhlhxo"/><path class="pa1ot6bmg"/><path class="g9_eu8bfj"/><path class="fsi7fbbnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parameters-duotone-thin" /></template>
<style>
.fsi7fbbnr {
  d: path("M13.5 15h5");
}

.g9_eu8bfj {
  d: path("M5.5 9h5");
}

.gg9qhlhxo {
  d: path("M8 4v16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k86txfbxx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mnh2g9b1h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 9h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pa1ot6bmg {
  d: path("M16 4v16");
}

.r4q7pxbjl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vvtjq3jew {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
