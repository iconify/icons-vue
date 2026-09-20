<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="lmbhihbzq"/><path class="xmg9uv4ey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pressure-falling-outline-regular" /></template>
<style>
.lmbhihbzq {
  d: path("m12 16 -5 -5");
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xmg9uv4ey {
  d: path("M10.5 11H7v3.5");
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
