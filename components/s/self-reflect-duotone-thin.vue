<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w5bqt9bao"/><path class="kyx8xyb8s"/><path class="d0mhxyezd"/><path class="uy91f4czm"/><path class="y07a50u1t"/><path class="an_usn22t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-reflect-duotone-thin" /></template>
<style>
.an_usn22t {
  d: path("M10.73 21.72a3 3 0 1 1 2.54 0");
}

.d0mhxyezd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.73 21.72a3 3 0 1 1 2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kyx8xyb8s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uy91f4czm {
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
}

.w5bqt9bao {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y07a50u1t {
  d: path("M5 13h14");
}

</style>
