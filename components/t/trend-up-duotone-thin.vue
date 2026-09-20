<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-1kzjblr"/><path class="m9d8bbb2i"/><path class="q0ddccbcl"/><path class="kk-764bgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trend-up-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kk-764bgz {
  d: path("M17 7h4v4");
}

.m9d8bbb2i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 7h4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q0ddccbcl {
  d: path("m3 17 6 -6 4 4 8 -8");
}

.r-1kzjblr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 17 6 -6 4 4 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
