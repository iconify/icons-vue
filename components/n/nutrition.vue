<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="clbhulbjp"/><path class="z3b8-ch_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nutrition" /></template>
<style>
.clbhulbjp {
  cx: 9.5px;
  cy: 12px;
  r: 6.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z3b8-ch_v {
  d: path("M9.5 5.25v13.5m0-6.75h6.75m2.25-8.25V7.5a1.25 1.25 0 0 0 2.5 0V3.75m-1.25 5v11.5");
}

</style>
