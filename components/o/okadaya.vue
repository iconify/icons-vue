<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g8nbydbqg"/><path class="hqd_lbrxe"/><path class="p676umbqe"/><path class="ppybvubgl"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:okadaya" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g8nbydbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.385 19.067v7.384m0-1.568l3.35-3.326m-2.28 2.268l2.622 2.615m19.812 0l-1.965-4.891m3.692 0l-2.345 6.644c-.156.443-.574.74-1.044.74h-.303m-7.078-5.527a1.846 1.846 0 0 0-3.692 0v1.2a1.846 1.846 0 0 0 3.692 0m0 1.845v-7.384m-8.619 2.966c.445-.445.757-.485 1.615-.485c.975 0 1.616.43 1.616 1.588v3.304");
}

.hqd_lbrxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.458 24.594c0 1.02-.82 1.846-1.832 1.846h-.643c-.67 0-1.214-.547-1.214-1.223s.543-1.223 1.214-1.223h2.478m7.536-1.961c.445-.445.756-.485 1.615-.485c.975 0 1.615.43 1.615 1.588v3.304");
}

.p676umbqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.227 24.594c0 1.02-.82 1.846-1.832 1.846h-.643c-.67 0-1.213-.547-1.213-1.223s.543-1.223 1.213-1.223h2.478m7.536-1.961c.445-.445.757-.485 1.615-.485c.975 0 1.616.43 1.616 1.588v3.304");
}

.ppybvubgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.997 24.594c0 1.02-.82 1.846-1.832 1.846h-.643c-.67 0-1.214-.547-1.214-1.223s.544-1.223 1.214-1.223H42m-36-.588a1.846 1.846 0 0 1 3.692 0v1.2a1.846 1.846 0 0 1-3.692 0z");
}

</style>
