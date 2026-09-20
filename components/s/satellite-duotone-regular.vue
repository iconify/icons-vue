<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x_lzie0od"/><path class="hgarhabko"/><path class="w0x5rgbcm"/><path class="jw0p8t42j"/><path class="b4-wc0yut"/><path class="k2kn5zbik"/><path class="omg7adb5g"/><path class="c60esnb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:satellite-duotone-regular" /></template>
<style>
.b4-wc0yut {
  d: path("M3.48 10.26a8 8 0 0 1 15.04 5.5");
}

.c60esnb_c {
  d: path("M6 20h10");
}

.hgarhabko {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m11 13 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jw0p8t42j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k2kn5zbik {
  d: path("m11 13 6 -6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.omg7adb5g {
  d: path("M11 13v7");
}

.w0x5rgbcm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x_lzie0od {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3.48 10.26a8 8 0 0 1 15.04 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
