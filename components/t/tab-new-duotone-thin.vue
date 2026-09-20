<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lid4b7x8u"/><path class="ior14cbcm"/><path class="mxollbc1y"/><path class="yeq6ekb5h"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="qvtmo6b3b"/><path class="a46bghb1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-new-duotone-thin" /></template>
<style>
.a46bghb1i {
  d: path("M18 10v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ior14cbcm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lid4b7x8u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19V9l2 -2h6l2 2v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mxollbc1y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oscmqi7_r {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

.qvtmo6b3b {
  d: path("M15 13h6");
}

.yeq6ekb5h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
