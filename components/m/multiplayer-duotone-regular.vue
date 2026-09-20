<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_tm5hr5z"/><path class="fnfc3vb6o"/><path class="o_8mz3s9v"/><path class="z02hhrbhf"/><path class="mdqmuqzrh"/><path class="rp7ii8bgy"/><path class="fim5wvb3d"/><path class="lhhiiffss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multiplayer-duotone-regular" /></template>
<style>
.fim5wvb3d {
  d: path("M5.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.fnfc3vb6o {
  fill: currentColor;
  d: path("M14 8v8h7V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lhhiiffss {
  d: path("M16.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mdqmuqzrh {
  d: path("M3 8v8h7V8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_8mz3s9v {
  fill: currentColor;
  d: path("M5.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o_tm5hr5z {
  fill: currentColor;
  d: path("M3 8v8h7V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rp7ii8bgy {
  d: path("M14 8v8h7V8Z");
}

.z02hhrbhf {
  fill: currentColor;
  d: path("M16.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
