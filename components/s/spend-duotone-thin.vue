<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xiota8z6p"/><path class="x7aiqk4zc"/><path class="jlpxneb5g"/><path class="wg8_ddc1f"/><path class="e0fatccfd"/><path class="wn519caci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spend-duotone-thin" /></template>
<style>
.e0fatccfd {
  d: path("M18 12h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.wg8_ddc1f {
  d: path("M6 12h6");
}

.wn519caci {
  d: path("m19 9 3 3 -3 3");
}

.x7aiqk4zc {
  d: path("M2 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.xiota8z6p {
  fill: currentColor;
  d: path("M2 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
