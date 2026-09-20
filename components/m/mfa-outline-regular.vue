<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ve2c5yb5g"/><path class="tpoo0acuc"/><path class="zc40h1bod"/><path class="p_g11-bmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mfa-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p_g11-bmp {
  d: path("M17 18h3");
}

.tpoo0acuc {
  d: path("M4 8a3 3 0 0 1 6 0");
}

.ve2c5yb5g {
  d: path("M2 10a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.zc40h1bod {
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v13a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
