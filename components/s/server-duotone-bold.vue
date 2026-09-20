<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cb89o3m_u"/><path class="g7y1om9dd"/><path class="w0cwozbjc"/><path class="olhk6j3ge"/><path class="e1vgu1brh"/><path class="jotdonbiv"/><path class="n2l08-bfj"/><path class="ccgk_xb3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:server-duotone-bold" /></template>
<style>
.cb89o3m_u {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v4.5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ccgk_xb3n {
  d: path("M7 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e1vgu1brh {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v4.5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.g7y1om9dd {
  fill: currentColor;
  d: path("M7 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jotdonbiv {
  d: path("M7 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n2l08-bfj {
  d: path("M4 15.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.olhk6j3ge {
  fill: currentColor;
  d: path("M7 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w0cwozbjc {
  fill: currentColor;
  d: path("M4 15.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
