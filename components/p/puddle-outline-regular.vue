<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d52t8wbsd"/><path class="gbe32p-qb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:puddle-outline-regular" /></template>
<style>
.d52t8wbsd {
  d: path("m12 4 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.gbe32p-qb {
  d: path("M3 15a9 3.5 0 1 0 18 0 9 3.5 0 1 0 -18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
