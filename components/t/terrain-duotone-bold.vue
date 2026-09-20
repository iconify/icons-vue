<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ny6-pzbfr"/><path class="hd0l8pb1q"/><path class="qaia1d1wv"/><path class="wt9iv5biz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:terrain-duotone-bold" /></template>
<style>
.hd0l8pb1q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ny6-pzbfr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 12 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qaia1d1wv {
  d: path("m2 12 6 -6 3 3 5 -5 5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wt9iv5biz {
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
}

</style>
