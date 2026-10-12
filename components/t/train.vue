<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="oex5vt_zf"/><rect class="k_c7n-byx"/><path class="sz0grsbiu"/><path class="gq2dgkb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:train" /></template>
<style>
.gq2dgkb4a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.75 17.25l-2.25 4m8.75-4l2.25 4");
}

.k_c7n-byx {
  width: 8.5px;
  height: 4.5px;
  x: 7.75px;
  y: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.oex5vt_zf {
  width: 13.5px;
  height: 14.5px;
  x: 5.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.5px;
}

.sz0grsbiu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 13.75h.01m6.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
