<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hdls9bcen"/><path class="x5-v1c34k"/><path class="l0vooab0i"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-schedule-duotone-bold" /></template>
<style>
.cfyvl-o0i {
  d: path("M16 12h4");
}

.hdls9bcen {
  fill: currentColor;
  d: path("M2 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l0vooab0i {
  d: path("M8 9v3h3");
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x5-v1c34k {
  d: path("M2 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

</style>
