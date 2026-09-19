<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2yhoepqr"/><path class="h_609abec"/><path class="dar9hojsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:origin-health" /></template>
<style>
.dar9hojsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.17 22.055c-1.643-1.643-1.644-4.317 0-5.96s4.317-1.643 5.96 0l9.85 9.85c1.643 1.643 1.643 4.318 0 5.96s-4.317 1.643-5.96 0z");
}

.h_609abec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.618 26.606c-4.16-4.16-4.16-10.903 0-15.062s10.904-4.16 15.063 0l9.85 9.85c4.16 4.16 4.16 10.903 0 15.063s-10.903 4.159-15.062 0z");
}

.n2yhoepqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.108 24.994a10.5 10.5 0 0 1 2.358-3.598l2.983-2.983m-2.983 18.042c4.162 4.161 10.907 4.161 15.068 0l9.851-9.851c4.152-4.162 4.152-10.897 0-15.059c-4.162-4.161-10.907-4.161-15.068 0L24 13.862");
}

</style>
