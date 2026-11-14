<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u-dbbte2p"/><path class="qpb2dbcmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shower-head" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qpb2dbcmt {
  d: path("M6.5 12a5.5 5.5 0 0 1 11 0Zm2 3.5h.01m3.49 0h.01m3.49 0h.01");
}

.u-dbbte2p {
  d: path("M3.5 3H9a3 3 0 0 1 3 3v1");
}

</style>
