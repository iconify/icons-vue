<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrmtxyafv"/><path class="u07qp3bhr"/><path class="kiz2lrbtx"/><path class="y_or9-s0p"/><path class="yqy8x4bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:top-n-tune-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kiz2lrbtx {
  d: path("M8 14h12");
}

.u07qp3bhr {
  d: path("M8 9h12");
}

.y_or9-s0p {
  d: path("M8 19h12");
}

.yqy8x4bvc {
  d: path("M5.5 2H3v9h2.5");
}

.zrmtxyafv {
  d: path("M8 4h12");
}

</style>
