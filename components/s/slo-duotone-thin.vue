<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0f0f2w0j"/><path class="jatp6jb0f"/><path class="gqnrk6bxj"/><path class="dotj7bbob"/><path class="jfhg8zbol"/><path class="aig5gcc6s"/><path class="me177l4bh"/><path class="qpg3-gppv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:slo-duotone-thin" /></template>
<style>
.a0f0f2w0j {
  fill: currentColor;
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.aig5gcc6s {
  d: path("m12 17 5 -5");
}

.dotj7bbob {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 3 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gqnrk6bxj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 17 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jatp6jb0f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jfhg8zbol {
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
}

.me177l4bh {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qpg3-gppv {
  d: path("m17 3 2 2 3 -3");
}

</style>
