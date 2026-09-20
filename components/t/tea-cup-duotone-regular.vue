<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l3bfc0bau"/><path class="a5svpccsg"/><path class="xl83b8b9f"/><path class="s7yzvqbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tea-cup-duotone-regular" /></template>
<style>
.a5svpccsg {
  d: path("M5 9v9h11V9");
}

.l3bfc0bau {
  fill: currentColor;
  d: path("M8 2h5v3H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s7yzvqbuw {
  d: path("M8 2h5v3H8Z");
}

.xl83b8b9f {
  d: path("M10 9V5");
}

</style>
