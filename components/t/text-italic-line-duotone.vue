<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3ug6dett"/><path class="wfrd3qbzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wfrd3qbzd {
  d: path("M9 22L15 2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y3ug6dett {
  d: path("M3 22H15M9 2H21");
}

</style>
