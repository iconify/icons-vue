<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qe5nt38fb"/><path class="h8x8ptj-p"/><path class="ll4cdbb5a"/><path class="filuri95n"/><path class="p9fnnqwai"/><path class="g7rxpleju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-chill-duotone-thin" /></template>
<style>
.filuri95n {
  d: path("M8 4v8m-4 0 8 -8");
}

.g7rxpleju {
  d: path("M4 20h14");
}

.h8x8ptj-p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16h11a3 3 0 1 1 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ll4cdbb5a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p9fnnqwai {
  d: path("M4 16h11a3 3 0 1 1 -3 3");
}

.qe5nt38fb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4v8m-4 0 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
