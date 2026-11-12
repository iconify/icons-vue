<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cz11_obym"/><path class="dbce2h2td"/><path class="pf4lixn8e"/><path class="z4t16fbxy"/><path class="jdt4fscuq"/><path class="m70uymbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-broken" /></template>
<style>
.cz11_obym {
  d: path("M19 12.2315L19.9546 11.2769C21.3182 9.91327 22 9.23148 22 8.38426C22 7.53704 21.3182 6.85525 19.9546 5.49167L18.5083 4.04537C17.1448 2.68179 16.463 2 15.6157 2C14.7685 2 14.0867 2.68179 12.7231 4.04537L4.04537 12.7231C2.68179 14.0867 2 14.7685 2 15.6157C2 16.463 2.68179 17.1448 4.04537 18.5083L5.49167 19.9546C6.85525 21.3182 7.53704 22 8.38426 22C9.23148 22 9.91327 21.3182 11.2769 19.9546L16.2315 15");
}

.dbce2h2td {
  d: path("M8.46436 8.46448L9.87857 9.87869");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdt4fscuq {
  d: path("M6.34326 10.5858L8.46458 12.7071");
}

.m70uymbtv {
  d: path("M10.5857 6.34314L12.707 8.46446");
}

.pf4lixn8e {
  d: path("M12.707 4.2218L14.1212 5.63602");
}

.z4t16fbxy {
  d: path("M4.22192 12.7072L5.63614 14.1214");
}

</style>
