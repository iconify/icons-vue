<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w59rsbfiv"/><path class="qc7u9l3jg"/><path class="yhmvkwnna"/><path class="u2ca2hb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wedding-invitation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qc7u9l3jg {
  d: path("m5 10l7 5l7-5");
}

.u2ca2hb-u {
  d: path("M10.75 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.w59rsbfiv {
  d: path("M6 10h12a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 10");
}

.yhmvkwnna {
  d: path("M6.25 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
