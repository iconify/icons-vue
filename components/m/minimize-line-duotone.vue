<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n07drobuw"/><path class="bvt-woblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-line-duotone" /></template>
<style>
.bvt-woblq {
  d: path("M22 2L15 9M15 3.14286V9H20.8571");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n07drobuw {
  d: path("M2 22L9 15M9 20.8571V15H3.14286");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
