<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_bfmcbrm"/><path class="irpgg1b9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irpgg1b9t {
  d: path("M9.5 11.5a4.5 4.5 0 0 1 9 0ZM11 15h.01M14 15h.01M17 15h.01m-4.51 3.5h.01m2.99 0h.01");
}

.k_bfmcbrm {
  d: path("M4.5 21V7.5a4 4 0 0 1 4-4h2A3.5 3.5 0 0 1 14 7");
}

</style>
