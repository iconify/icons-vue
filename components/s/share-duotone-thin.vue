<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgscl2bdj"/><path class="s8txduonj"/><path class="flxcmubzb"/><path class="p_8lzlbte"/><path class="pz7omhb0s"/><path class="zirb-hbnv"/><path class="x8ux9pb9v"/><path class="dvobmj5db"/><path class="otd842a5m"/><path class="x6ykmmben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:share-duotone-thin" /></template>
<style>
.dvobmj5db {
  d: path("M14 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.flxcmubzb {
  fill: currentColor;
  d: path("M14 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.otd842a5m {
  d: path("m9.5 10.5 5 -5");
}

.p_8lzlbte {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 10.5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pz7omhb0s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 13.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s8txduonj {
  fill: currentColor;
  d: path("M14 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x6ykmmben {
  d: path("m9.5 13.5 5 5");
}

.x8ux9pb9v {
  d: path("M14 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xgscl2bdj {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zirb-hbnv {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
