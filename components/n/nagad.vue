<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m26zalbso"/><path class="a4v82zbpm"/><path class="a6h1jkbio"/><path class="eni_kyfoa"/><path class="w8-j1zb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nagad" /></template>
<style>
.a4v82zbpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.92 25.893c-.062-4.213 2.564-12.09 11.48-15.938l-3.603-6.412c-5.374 2.626-12.58 11.664-7.878 22.35");
}

.a6h1jkbio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.136 12.409a16.8 16.8 0 0 0-2.921 8.842c1.839-3.791 7.725-9.648 17.419-9.077l-.336-7.347a18 18 0 0 0-10.613 3.856");
}

.eni_kyfoa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.465 12.153a16.5 16.5 0 0 0-10.569 8.127c3.347-2.56 11.238-5.145 19.64-.278l3.002-6.714a17.75 17.75 0 0 0-9.924-1.532");
}

.m26zalbso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.88 6.398a19.347 19.347 0 1 0 23.516 12.987");
}

.w8-j1zb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.438 20.07a11.604 11.604 0 1 0 19.046-2.772");
}

</style>
