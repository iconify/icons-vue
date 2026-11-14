<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sq9bpubzn"/><path class="r_fkeob1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:photo-book" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r_fkeob1p {
  d: path("M14.75 15.5L17 12l2.25 3.5M18 8.5h.01");
}

.sq9bpubzn {
  d: path("M12 6C9.5 4 6 4 2.5 5v14c3.5-1 7-1 9.5 1c2.5-2 6-2 9.5-1V5c-3.5-1-7-1-9.5 1m0 0v14");
}

</style>
