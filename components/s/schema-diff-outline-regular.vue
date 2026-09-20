<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="liom1epye"/><path class="m61z8ufvi"/><path class="gev0055ej"/><path class="jnfz-wh9g"/><path class="n10kxpbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:schema-diff-outline-regular" /></template>
<style>
.gev0055ej {
  d: path("M13.5 6a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
}

.jnfz-wh9g {
  d: path("M13.5 9H22");
}

.liom1epye {
  d: path("M2 6a2 2 0 0 1 2 -2h4.5a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.m61z8ufvi {
  d: path("M2 9h8.5");
}

.n10kxpbvp {
  d: path("M15.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
