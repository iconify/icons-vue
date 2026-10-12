<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q3ey8eb2r"/><path class="z5x8blbgv"/><path class="z9r9s2j1l"/><path class="uy4u_it9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tomato-vine-sharp" /></template>
<style>
.q3ey8eb2r {
  d: path("M12.25 21.25c-1-2.25-1-4.25 0-6.5s1-4.25 0-6.5s-1-3.25 0-5.5");
}

.uy4u_it9z {
  d: path("m5.25 10l.5-1.75l.5 1.75m11.5 5l.5-1.75l.5 1.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5x8blbgv {
  d: path("M11.6 7.25L8.311 5.292L5.75 7m6.15 4.75l3.642-1.214L18.25 12");
}

.z9r9s2j1l {
  d: path("M2.75 10a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm12.5 5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
