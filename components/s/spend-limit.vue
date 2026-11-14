<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrvtt4bhz"/><path class="oalskum9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spend-limit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrvtt4bhz {
  d: path("M6 8h12a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 8M2.5 4h19");
}

.oalskum9i {
  d: path("M9.25 13.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
