<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="v4a65sbgm"/><path class="l47x73bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shadow-linear" /></template>
<style>
.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l47x73bux {
  stroke-linecap: round;
  d: path("M16 16L19.0727 19.0727M18 13L21.1151 16.1151M13 18L16.1148 21.1148M19 9L22.0019 12.0019M9 19L12.0014 22.0014");
}

.v4a65sbgm {
  d: path("M17.0002 20.6601C12.2173 23.4211 6.10139 21.7831 3.33999 17.0001C0.578493 12.2171 2.21729 6.10106 7.00019 3.33906C8.94979 2.21406 11.1209 1.81906 13.196 2.07106C16.2117 2.43606 19.0246 4.16606 20.6605 7.00006C22.2963 9.83306 22.388 13.1341 21.1967 15.9291C20.377 17.8511 18.9498 19.5341 17.0002 20.6601Z");
}

</style>
