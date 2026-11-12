<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nx9b_s0ui"/><path class="itvkagoch"/><path class="t4ug9nsrr"/><path class="afiszmbnt"/><path class="zj2p4py0y"/><path class="cwatz7g8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-cross-broken" /></template>
<style>
.afiszmbnt {
  d: path("M8.53613 4.68853C9.99986 4.2911 11.511 4.14983 13.0085 4.26472");
}

.cwatz7g8l {
  d: path("M22 5.00002L19 8.00001M19 8.00001L16 11M19 8.00001L16 5M19 8.00001L21.9999 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itvkagoch {
  d: path("M5.33301 12.295C7.42965 10.032 10.2681 9.05764 13.0035 9.37195");
}

.nx9b_s0ui {
  d: path("M8.66699 15.8931C10.5079 13.9061 13.4927 13.9061 15.3337 15.8931");
}

.t4ug9nsrr {
  d: path("M2 8.69693C2.78921 7.84509 3.64848 7.11498 4.5578 6.50659");
}

.zj2p4py0y {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
}

</style>
