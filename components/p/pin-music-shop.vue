<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gp8gi8umf"/><path class="sz8tdbbui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-music-shop" /></template>
<style>
.gp8gi8umf {
  d: path("M9 11a5 5 0 1 0 4 4a3.5 3.5 0 1 0-4-4m6-2l3.25-3.25m3.091-3.091za1.5 1.5 0 0 1 0 2.121L20.28 5.841a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l1.061-1.061a1.5 1.5 0 0 1 2.121 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sz8tdbbui {
  d: path("M6.25 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
