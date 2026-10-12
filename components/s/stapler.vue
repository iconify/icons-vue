<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v_mi5z-ws"/><rect class="fq13zebzr"/><path class="ywhg-5pyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stapler" /></template>
<style>
.fq13zebzr {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 17.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_mi5z-ws {
  d: path("M3.75 13c0-1.35.95-2.5 2.25-2.75l11.75-2.3a2.5 2.5 0 0 1 3 2.45v.4a2 2 0 0 1-1.6 1.95l-13 2.6a2 2 0 0 1-2.4-1.95Z");
}

.ywhg-5pyi {
  d: path("M5 15.25v2.5");
}

</style>
