<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wp2qpob0e"/><path class="fvtn0_xol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moka-pot" /></template>
<style>
.fvtn0_xol {
  d: path("M16.4 7.25h2.85L18 12.75M7.6 7.25l-2.35-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wp2qpob0e {
  d: path("M10.5 2.75h3m-5.25 3h7.5q1 0 .78.97l-1.06 4.56q-.22.97-.06 1.96l1.18 7.02q.16.99-.84.99h-7.5q-1 0-.84-.99l1.18-7.02q.16-.99-.06-1.96L7.47 6.72q-.22-.97.78-.97m.5 6.5h6.5");
}

</style>
