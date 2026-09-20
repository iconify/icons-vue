<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vffpa5rfz"/><path class="xr0buybxj"/><path class="h67al40ex"/><path class="wre--v3de"/><path class="ned58dbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:treadmill-duotone-thin" /></template>
<style>
.h67al40ex {
  d: path("M2 19h13v-4H2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ned58dbax {
  d: path("M16 8h6V4h-6Z");
}

.vffpa5rfz {
  fill: currentColor;
  d: path("M2 19h13v-4H2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wre--v3de {
  d: path("M15 17h4V8");
}

.xr0buybxj {
  fill: currentColor;
  d: path("M16 8h6V4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
