<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gm51h172o"/><path class="cxv48ubbv"/><path class="ys_g-1bhp"/><path class="vlcef6m_c"/><path class="b4-wc0yut"/><path class="k2kn5zbik"/><path class="omg7adb5g"/><path class="c60esnb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:satellite-duotone-bold" /></template>
<style>
.b4-wc0yut {
  d: path("M3.48 10.26a8 8 0 0 1 15.04 5.5");
}

.c60esnb_c {
  d: path("M6 20h10");
}

.cxv48ubbv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m11 13 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gm51h172o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3.48 10.26a8 8 0 0 1 15.04 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k2kn5zbik {
  d: path("m11 13 6 -6");
}

.omg7adb5g {
  d: path("M11 13v7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vlcef6m_c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys_g-1bhp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
