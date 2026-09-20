<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="quua95b2b"/><path class="mjxjq9e4f"/><path class="bzecsub_a"/><path class="y_or9-s0p"/><path class="oeboj9bgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:test-select-duotone-thin" /></template>
<style>
.bzecsub_a {
  d: path("M8 12h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mjxjq9e4f {
  d: path("M8 5h12");
}

.oeboj9bgs {
  d: path("m3 9 3 3 -3 3Z");
}

.quua95b2b {
  fill: currentColor;
  d: path("m3 9 3 3 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y_or9-s0p {
  d: path("M8 19h12");
}

</style>
