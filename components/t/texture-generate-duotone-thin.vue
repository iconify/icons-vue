<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zp7m0nbel"/><path class="sf7s7wb6x"/><path class="n2j__bcmh"/><path class="miofc3chu"/><path class="aig5gcc6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:texture-generate-duotone-thin" /></template>
<style>
.aig5gcc6s {
  d: path("m12 17 5 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.miofc3chu {
  d: path("m9 15 6 -6");
}

.n2j__bcmh {
  d: path("m7 12 4 -4");
}

.sf7s7wb6x {
  d: path("m12 2 6 6v8l-6 6 -6 -6V8Z");
}

.zp7m0nbel {
  fill: currentColor;
  d: path("m12 2 6 6v8l-6 6 -6 -6V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
