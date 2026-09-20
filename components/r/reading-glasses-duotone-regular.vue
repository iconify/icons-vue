<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kryimcc7j"/><path class="j0thbqdzb"/><path class="znn_tgx5z"/><path class="rp--5qbrh"/><path class="khp0b8bxr"/><path class="tk14kvbjb"/><path class="z27xoybfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reading-glasses-duotone-regular" /></template>
<style>
.j0thbqdzb {
  fill: currentColor;
  d: path("M13 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.khp0b8bxr {
  d: path("M10.5 13h3");
}

.kryimcc7j {
  fill: currentColor;
  d: path("M3 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rp--5qbrh {
  d: path("M13 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.tk14kvbjb {
  d: path("m3 10 2 -2");
}

.z27xoybfi {
  d: path("m21 10 -2 -2");
}

.znn_tgx5z {
  d: path("M3 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
