<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zu-ymbcar"/><path class="yd1dd2b-v"/><path class="kj325sbuw"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="lmbhihbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:risk-low-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kj325sbuw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 16 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lmbhihbzq {
  d: path("m12 16 -5 -5");
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.yd1dd2b-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

.zu-ymbcar {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
