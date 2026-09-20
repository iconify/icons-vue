<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cgousu48d"/><path class="kwbe3flqa"/><path class="exbw4cc5o"/><path class="reszlpgvw"/><path class="pxcz33phn"/><path class="a-xc2ibwn"/><path class="u46xm9b9w"/><path class="g6v1wdg_x"/><path class="q1ae0k4gd"/><path class="z91-mkbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sprint-duotone-thin" /></template>
<style>
.a-xc2ibwn {
  d: path("M12 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.cgousu48d {
  fill: currentColor;
  d: path("M12 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.exbw4cc5o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12 6 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g6v1wdg_x {
  d: path("M10 12 6 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwbe3flqa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pxcz33phn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q1ae0k4gd {
  d: path("m14 16 4 4");
}

.reszlpgvw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 16 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u46xm9b9w {
  d: path("m14 8 -4 4 4 4");
}

.z91-mkbau {
  d: path("M3 20h5");
}

</style>
