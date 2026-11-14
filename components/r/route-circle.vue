<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_lkap-rx"/><path class="hi0n-nu5e"/><path class="nxd8ey-0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:route-circle" /></template>
<style>
.hi0n-nu5e {
  fill: currentColor;
  d: path("M8.75 5.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxd8ey-0f {
  d: path("M18.5 13.5c-2-2-3.25-3.75-3.25-6a3.25 3.25 0 0 1 6.5 0c0 2.25-1.25 4-3.25 6");
}

.p_lkap-rx {
  d: path("M10.5 5.5a8 8 0 1 0 8 8");
}

</style>
