<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="hujf6nb_f"/><path class="q6_fpy0-m"/><path class="i_-4dlb6s"/><circle class="kelpoib0q"/><path class="spcionb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pediatrician" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hujf6nb_f {
  cx: 8.5px;
  cy: 5.75px;
  r: 2.5px;
}

.i_-4dlb6s {
  d: path("M6.5 11.5L6 15a2.5 2.5 0 0 0 5 0l-.5-3.5");
}

.kelpoib0q {
  cx: 19.25px;
  cy: 13.75px;
  r: 1.5px;
}

.q6_fpy0-m {
  d: path("M2.75 21.25V17a5.75 5.75 0 0 1 11.5 0v4.25Z");
}

.spcionb3q {
  d: path("M17.25 21.25v-1.5a2 2 0 0 1 4 0v1.5Z");
}

</style>
