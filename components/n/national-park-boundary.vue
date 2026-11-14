<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5_oj5bzd"/><path class="ecmd3gboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:national-park-boundary" /></template>
<style>
.e5_oj5bzd {
  d: path("m4.077 5.551l4.25-1.771a1.75 1.75 0 0 1 1.346 0l4.654 1.94a1.75 1.75 0 0 0 1.346 0l2.904-1.21A1.75 1.75 0 0 1 21 6.125v10.708a1.75 1.75 0 0 1-1.077 1.616l-4.25 1.771a1.75 1.75 0 0 1-1.346 0l-4.654-1.94a1.75 1.75 0 0 0-1.346 0l-2.904 1.21A1.75 1.75 0 0 1 3 17.875V7.167a1.75 1.75 0 0 1 1.077-1.616");
}

.ecmd3gboi {
  d: path("M13.539 7.771a4.5 4.5 0 0 1 2.69 2.69m0 3.078a4.5 4.5 0 0 1-2.69 2.69m-3.078 0a4.5 4.5 0 0 1-2.69-2.69m0-3.078a4.5 4.5 0 0 1 2.69-2.69");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
