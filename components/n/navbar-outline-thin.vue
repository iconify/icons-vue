<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_snsacfd"/><path class="gswswg2-b"/><path class="hv3ppsbji"/><path class="korq7_l8k"/><path class="m-p3hbclp"/><path class="hc7fbd-jo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:navbar-outline-thin" /></template>
<style>
.gswswg2-b {
  d: path("M5 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hc7fbd-jo {
  d: path("M4 19h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv3ppsbji {
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.korq7_l8k {
  d: path("M17 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.m-p3hbclp {
  d: path("M4 15h16");
}

.w_snsacfd {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
