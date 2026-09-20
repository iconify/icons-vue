<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ppdwmrgka"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="ulu3xjbcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:store-policy-duotone-bold" /></template>
<style>
.ppdwmrgka {
  fill: currentColor;
  d: path("M9 12h6v3l-3 3 -3 -3Z");
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

.tp7101bon {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

.ulu3xjbcr {
  d: path("M9 12h6v3l-3 3 -3 -3Z");
}

.yb0d-pkkp {
  d: path("M4 8v14h16V8");
}

</style>
