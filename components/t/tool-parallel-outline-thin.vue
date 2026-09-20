<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tlah7acnn"/><path class="elo_ccj2r"/><path class="yz_nd208h"/><path class="zcoymgb5h"/><path class="xpqmchyzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tool-parallel-outline-thin" /></template>
<style>
.elo_ccj2r {
  d: path("M9 4v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tlah7acnn {
  d: path("M6 13a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.xpqmchyzd {
  d: path("M14.5 13v5");
}

.yz_nd208h {
  d: path("M15 4v7");
}

.zcoymgb5h {
  d: path("M9.5 13v5");
}

</style>
