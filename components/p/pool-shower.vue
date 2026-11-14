<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdnd0h2bk"/><path class="c_o37cqdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pool-shower" /></template>
<style>
.c_o37cqdm {
  d: path("M10.927 6h4.146a1.5 1.5 0 0 1 1.342.829l.335.671a1.036 1.036 0 0 1-.927 1.5h-5.646a1.036 1.036 0 0 1-.927-1.5l.335-.671A1.5 1.5 0 0 1 10.927 6M10 12l-.5 2m3.5-2v3m3-3l.5 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdnd0h2bk {
  d: path("M5 21V5a2 2 0 0 1 2-2h6v3");
}

</style>
