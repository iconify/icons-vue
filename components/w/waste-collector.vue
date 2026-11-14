<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rad1anbsu"/><path class="ddsazbbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:waste-collector" /></template>
<style>
.ddsazbbjs {
  d: path("M10 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rad1anbsu {
  d: path("M16.5 16.5H9V7a2 2 0 0 1 2-2h5.5Zm0-7.5H19l2.5 3v4.5h-5M2.5 9h3.75l-.5 6.5H3Z");
}

</style>
