<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g7esaduey"/><path class="y_h1uhbbv"/><path class="k-sgg11ok"/><path class="yrtvvab0c"/><path class="wn519caci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:message-queue-duotone-bold" /></template>
<style>
.g7esaduey {
  fill: currentColor;
  d: path("M2 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k-sgg11ok {
  d: path("M2 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wn519caci {
  d: path("m19 9 3 3 -3 3");
}

.y_h1uhbbv {
  fill: currentColor;
  d: path("M12 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yrtvvab0c {
  d: path("M12 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
