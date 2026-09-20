<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v60o5chyb"/><path class="aq3-xgb-k"/><path class="jqlnd8iax"/><path class="u1kydjbkc"/><path class="fbn42bcxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rent-due-duotone-bold" /></template>
<style>
.aq3-xgb-k {
  fill: currentColor;
  d: path("M14 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fbn42bcxw {
  d: path("M14 8h8");
}

.jqlnd8iax {
  d: path("M2 20v-7l5 -5 5 5v7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u1kydjbkc {
  d: path("M14 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.v60o5chyb {
  fill: currentColor;
  d: path("M2 20v-7l5 -5 5 5v7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
