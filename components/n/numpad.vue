<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="izyf3bcdo"/><path class="l65mxqbum"/><path class="d7y0pzdah"/><path class="kqd5ziwbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:numpad" /></template>
<style>
.d7y0pzdah {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 17.25H12");
}

.izyf3bcdo {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.kqd5ziwbj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 17.25h.01");
}

.l65mxqbum {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 6.75h.01m3.74 0h.01m3.74 0h.01m-7.51 3.5h.01m3.74 0h.01m3.74 0h.01m-7.51 3.5h.01m3.74 0h.01m3.74 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
