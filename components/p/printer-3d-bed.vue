<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yi6tzxb9n"/><path class="rpk_k1y0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:printer-3d-bed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpk_k1y0b {
  d: path("M4.75 15h14.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25H4.75a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 4.75 15M12 7.5V15");
}

.yi6tzxb9n {
  d: path("m3.873 12.426l2.133-4A1.75 1.75 0 0 1 7.55 7.5h8.9a1.75 1.75 0 0 1 1.544.926l2.133 4A1.75 1.75 0 0 1 18.583 15H5.417a1.75 1.75 0 0 1-1.544-2.574");
}

</style>
