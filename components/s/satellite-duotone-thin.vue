<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hw5b_obrw"/><path class="z42vvdbnp"/><path class="uh-cccc7u"/><path class="rnv2o9bje"/><path class="b4-wc0yut"/><path class="k2kn5zbik"/><path class="omg7adb5g"/><path class="c60esnb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:satellite-duotone-thin" /></template>
<style>
.b4-wc0yut {
  d: path("M3.48 10.26a8 8 0 0 1 15.04 5.5");
}

.c60esnb_c {
  d: path("M6 20h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hw5b_obrw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3.48 10.26a8 8 0 0 1 15.04 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k2kn5zbik {
  d: path("m11 13 6 -6");
}

.omg7adb5g {
  d: path("M11 13v7");
}

.rnv2o9bje {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uh-cccc7u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z42vvdbnp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 13 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
