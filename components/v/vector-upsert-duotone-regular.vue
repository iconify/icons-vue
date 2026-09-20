<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sw_hwrbxs"/><path class="v2mnclz8q"/><path class="wa9pjob9g"/><path class="zoomnj6dr"/><path class="knb00ei4h"/><path class="d_b1a31kv"/><path class="bk6uwfbvv"/><path class="slz7u0oyn"/><path class="d69_otb1b"/><path class="scs5jbhoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vector-upsert-duotone-regular" /></template>
<style>
.bk6uwfbvv {
  d: path("M5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.d_b1a31kv {
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.d69_otb1b {
  d: path("M18 4v6");
}

.knb00ei4h {
  d: path("M5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.scs5jbhoc {
  d: path("m15 7 3 3 3 -3");
}

.slz7u0oyn {
  d: path("M2 19.5A2.5 2.5 0 0 1 4.5 17h15a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-15A2.5 2.5 0 0 1 2 19.5");
}

.sw_hwrbxs {
  fill: currentColor;
  d: path("M5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v2mnclz8q {
  fill: currentColor;
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wa9pjob9g {
  fill: currentColor;
  d: path("M5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zoomnj6dr {
  fill: currentColor;
  d: path("M2 19.5A2.5 2.5 0 0 1 4.5 17h15a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-15A2.5 2.5 0 0 1 2 19.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
