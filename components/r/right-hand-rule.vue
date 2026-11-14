<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="egvo42tjv"/><path class="tobjl_bdz"/><path class="dbgt_sbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:right-hand-rule" /></template>
<style>
.dbgt_sbhw {
  d: path("m13.5 7l1-1l1 1");
}

.egvo42tjv {
  d: path("M7.5 4.75a1.75 1.75 0 0 1 3.5 0V12h7.75a1.75 1.75 0 0 1 0 3.5H15.5v3a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3V16l-4-4a1.6 1.6 0 0 1 2.25-2.25L7.5 11.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tobjl_bdz {
  d: path("M17 3.5A2.5 2.5 0 1 1 14.5 6");
}

</style>
