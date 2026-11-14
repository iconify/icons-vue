<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w8uij4eqn"/><path class="u985c_bse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mention-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u985c_bse {
  d: path("M13.5 10.5V15a2 2 0 0 0 4 0v-1.5a7 7 0 1 0-3.5 6M19 2q.5 2.5 3 3q-2.5.5-3 3q-.5-2.5-3-3q2.5-.5 3-3");
}

.w8uij4eqn {
  d: path("M7.5 13.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
