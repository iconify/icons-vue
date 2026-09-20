<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q4vnxcbew"/><path class="w88m64x8i"/><path class="n0o_vcb_x"/><path class="c-vnm8iux"/><path class="zb-4rhbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:timeout-flow-duotone-thin" /></template>
<style>
.c-vnm8iux {
  d: path("M15 12h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0o_vcb_x {
  d: path("M7 9v3h2.5");
}

.q4vnxcbew {
  fill: currentColor;
  d: path("M2 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w88m64x8i {
  d: path("M2 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.zb-4rhbsf {
  d: path("M21 7v10");
}

</style>
