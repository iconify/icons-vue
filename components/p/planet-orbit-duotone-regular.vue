<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mhygvef8z"/><path class="jzeve79sx"/><path class="xm-p8ezyy"/><path class="i_q2pwdgu"/><path class="ymw3aibdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:planet-orbit-duotone-regular" /></template>
<style>
.i_q2pwdgu {
  d: path("M3.54 10.92a9 9 0 0 1 16.92 0");
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mhygvef8z {
  fill: currentColor;
  d: path("M7 14a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
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

.xm-p8ezyy {
  d: path("M7 14a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
