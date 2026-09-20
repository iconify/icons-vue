<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lo7kp72nh"/><path class="ze3njkbee"/><path class="t47xolklb"/><path class="o9qd50bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swimming-outline-regular" /></template>
<style>
.lo7kp72nh {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9qd50bgb {
  d: path("M2 18h3l3 -3 3 3 3 -3 3 3h5");
}

.t47xolklb {
  d: path("M9 11h8");
}

.ze3njkbee {
  d: path("m9 10 4 -4");
}

</style>
