<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y_xsmq0bc"/><path class="vssu5c7_s"/><path class="k8zkzcbex"/><path class="q55n1xk3r"/><path class="tq7kvx37d"/><path class="g4uzw-b-k"/><path class="z1aqs2_3g"/><path class="vhfiyem-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:washing-machine-line-duotone" /></template>
<style>
.g4uzw-b-k {
  d: path("M6.5 5.5H9.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8zkzcbex {
  d: path("M11 21H13C16.7712 21 18.6569 21 19.8284 19.8284C21 18.6569 21 16.7712 21 13V10C21 6.22876 21 4.34315 19.8284 3.17157C18.6569 2 16.7712 2 13 2H11C7.22876 2 5.34315 2 4.17157 3.17157C3 4.34315 3 6.22876 3 10V13C3 16.7712 3 18.6569 4.17157 19.8284C5.34315 21 7.22876 21 11 21Z");
}

.q55n1xk3r {
  d: path("M3 9H21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tq7kvx37d {
  d: path("M15 15C15 16.6569 13.6569 18 12 18C10.3431 18 9 16.6569 9 15C9 13.3431 10.3431 12 12 12C13.6569 12 15 13.3431 15 15Z");
}

.vhfiyem-h {
  stroke-linejoin: round;
  d: path("M17.5 5.5H17.5001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vssu5c7_s {
  d: path("M18 22V21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y_xsmq0bc {
  d: path("M6 22V21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z1aqs2_3g {
  stroke-linejoin: round;
  d: path("M14.5 5.5H14.5001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
