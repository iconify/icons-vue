<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jy0ydi2tc"/><path class="yrxnqacsr"/><path class="qyssvt-aa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:topographic-map-sharp" /></template>
<style>
.jy0ydi2tc {
  d: path("m4.4 5.75l3.45-1.5L9 3.75l1.15.48l3.7 1.54l1.15.48l1.15-.5l3.45-1.5l1.15-.5v14l-1.15.5l-3.45 1.5l-1.15.5l-1.15-.48l-3.7-1.54L9 17.75l-1.15.5l-3.45 1.5l-1.15.5v-14z");
}

.qyssvt-aa {
  d: path("M12.75 12h2.75v2.1c0 1.25-1.25 2.4-3 2.4H10V12z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrxnqacsr {
  d: path("M3.25 15C4.5 11.75 7 9 11.5 8.75s7.5 1.75 9.25 4.5");
}

</style>
