<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e11cb2_va"/><path class="q2p8t8bxl"/><path class="beu6gsbmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:measuring-spoons" /></template>
<style>
.beu6gsbmp {
  d: path("M16.75 20.75a3.5 2.5 90 1 1 0-7a3.5 2.5 90 1 1 0 7m.05-7l.4-5.5");
}

.e11cb2_va {
  cx: 17.25px;
  cy: 5.75px;
  r: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q2p8t8bxl {
  d: path("M4 18.75a4.25 3-45 1 1 6-6a4.25 3-45 1 1-6 6m6-6l5.45-5.25");
}

</style>
