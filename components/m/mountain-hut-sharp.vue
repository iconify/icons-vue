<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gyhtaq2xk"/><path class="i5_elqbnh"/><path class="ecl_f959t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mountain-hut-sharp" /></template>
<style>
.ecl_f959t {
  d: path("M10.75 21.25v-3h2.5v3");
}

.gyhtaq2xk {
  d: path("m2.75 16.5l5.5-10l3.25 4.75l2.5-3.5l7.25 9.75");
}

.i5_elqbnh {
  d: path("M7.5 20.25V16.5l.77-.64l2.96-2.47l.77-.64l.77.64l2.96 2.47l.77.64v4.75h-9z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
