<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s1r4963pp"/><path class="s09hy0b0y"/><path class="wcigoab1j"/><path class="m0f5ny81l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:solar-panel-outline-bold" /></template>
<style>
.m0f5ny81l {
  d: path("M5 20h8");
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s1r4963pp {
  d: path("m4 14 6 -6h10l-6 6Z");
}

.wcigoab1j {
  d: path("M9 14v6");
}

</style>
