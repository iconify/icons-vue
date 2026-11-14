<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iee3p_blp"/><path class="jpi8983ox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tote-bin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iee3p_blp {
  d: path("M3.5 8h17L19 20H5Zm0 0L6 5h12l2.5 3");
}

.jpi8983ox {
  d: path("M10.25 11h3.5A1.25 1.25 0 0 1 15 12.25a1.25 1.25 0 0 1-1.25 1.25h-3.5A1.25 1.25 0 0 1 9 12.25A1.25 1.25 0 0 1 10.25 11");
}

</style>
