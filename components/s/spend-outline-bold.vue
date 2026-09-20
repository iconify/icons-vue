<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x7aiqk4zc"/><path class="jlpxneb5g"/><path class="wg8_ddc1f"/><path class="e0fatccfd"/><path class="wn519caci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spend-outline-bold" /></template>
<style>
.e0fatccfd {
  d: path("M18 12h4");
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
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

</style>
