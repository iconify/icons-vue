<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="astdsob4c"/><path class="yrxnqacsr"/><path class="uv2jmabqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:topographic-map" /></template>
<style>
.astdsob4c {
  d: path("m4.4 5.75l3.45-1.5q1.15-.5 2.3-.02l3.7 1.54q1.15.48 2.3-.02l3.45-1.5q1.15-.5 1.15.75v11.5q0 1.25-1.15 1.75l-3.45 1.5q-1.15.5-2.3.02l-3.7-1.54q-1.15-.48-2.3.02l-3.45 1.5q-1.15.5-1.15-.75V7.5q0-1.25 1.15-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uv2jmabqr {
  d: path("M12.75 12c1.75 0 2.75.85 2.75 2.1s-1.25 2.4-3 2.4s-2.5-.85-2.5-2.1s1-2.4 2.75-2.4");
}

.yrxnqacsr {
  d: path("M3.25 15C4.5 11.75 7 9 11.5 8.75s7.5 1.75 9.25 4.5");
}

</style>
