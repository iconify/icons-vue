<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_8p2fisw"/><path class="n96lwfw4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-horizontal-linear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n96lwfw4e {
  d: path("M6 16L18 16M13.875 20L18 16L13.875 12");
}

.q_8p2fisw {
  d: path("M18 8L6 8M10.125 12L6 8L10.125 4");
}

</style>
