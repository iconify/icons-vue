<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v1-fmxxhj"/><path class="h1cr44bva"/><path class="kgpu6-15k"/><path class="rfdwl-jei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:squash-layer-outline-regular" /></template>
<style>
.h1cr44bva {
  d: path("M3 12a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.kgpu6-15k {
  d: path("m10 15.5 2 -2 2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rfdwl-jei {
  d: path("m10 18.5 2 -2 2 2");
}

.v1-fmxxhj {
  d: path("M3 4.5A2.5 2.5 0 0 1 5.5 2h13A2.5 2.5 0 0 1 21 4.5 2.5 2.5 0 0 1 18.5 7h-13A2.5 2.5 0 0 1 3 4.5");
}

</style>
