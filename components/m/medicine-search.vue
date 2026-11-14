<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qchc9hjmv"/><path class="u9_vgnv3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medicine-search" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qchc9hjmv {
  d: path("M2.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0m13 5.5L21 21");
}

.u9_vgnv3v {
  d: path("M12.828 7.172za2 2 0 0 1 0 2.828L10 12.828a2 2 0 0 1-2.828 0a2 2 0 0 1 0-2.828L10 7.172a2 2 0 0 1 2.828 0M8.586 8.586l2.828 2.828");
}

</style>
