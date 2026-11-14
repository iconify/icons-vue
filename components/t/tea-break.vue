<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mlj_upb_s"/><path class="s_7ta9brz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tea-break" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mlj_upb_s {
  d: path("M5.5 10H16v3a5 5 0 0 1-5 5h-.5a5 5 0 0 1-5-5Z");
}

.s_7ta9brz {
  d: path("M16 11h1.25a2.25 2.25 0 0 1 0 4.5h-2M3.5 21h16M9 7.25C7.75 6 10.25 4.5 9 2.75m4 4.5C11.75 6 14.25 4.5 13 2.75");
}

</style>
