<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="tz2gxg9vp"/><path class="ihgl1bbop"/><path class="s6lq_ibpx"/><path class="zvy8fhb2v"/><path class="bo51iypxr"/><path class="xz82qebme"/><path class="lz9b4vtgl"/><path class="glv5tabri"/><path class="x-fkne0xd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:typhoon-duotone-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.glv5tabri {
  d: path("M19 12V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihgl1bbop {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 12a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lz9b4vtgl {
  d: path("M5 12a7 7 0 0 1 14 0");
}

.s6lq_ibpx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 12V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tz2gxg9vp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 12a7 7 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x-fkne0xd {
  d: path("M5 12v7");
}

.xz82qebme {
  d: path("M19 12a7 7 0 0 1 -14 0");
}

.zvy8fhb2v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
