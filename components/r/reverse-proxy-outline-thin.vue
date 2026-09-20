<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7pgrp-wx"/><path class="u8r6qcbvo"/><path class="jqa2x_bhs"/><path class="tgk1fwb-a"/><path class="d6_dczb3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reverse-proxy-outline-thin" /></template>
<style>
.d6_dczb3z {
  d: path("M20 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e7pgrp-wx {
  d: path("M2 12h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqa2x_bhs {
  d: path("M19 7.5 14.5 12l4.5 4.5");
}

.tgk1fwb-a {
  d: path("M14.5 12H19");
}

.u8r6qcbvo {
  d: path("M8 10a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H10a2 2 0 0 1 -2 -2Z");
}

</style>
