<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i99jpsfam"/><path class="k_vfb7aeb"/><path class="hi5e58bpt"/><path class="o68l3dmms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-alphabetically-linear" /></template>
<style>
.hi5e58bpt {
  d: path("M8 17H3");
}

.i99jpsfam {
  d: path("M13 7L3 7");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_vfb7aeb {
  d: path("M10 12H3");
}

.o68l3dmms {
  stroke-linejoin: round;
  d: path("M12 17L13.6364 13.3636M21 17L19.3636 13.3636L16.5 7L13.6364 13.3636M13.6364 13.3636H19.3636");
}

</style>
