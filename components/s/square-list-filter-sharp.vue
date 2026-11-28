<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x-_5ilohg"/><path class="ik637wben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-list-filter-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ik637wben {
  d: path("M7 8L17 8M8.5 12L15.5 12M10 16L14 16");
}

.x-_5ilohg {
  d: path("M3 3L21 3L21 21L3 21L3 3Z");
}

</style>
