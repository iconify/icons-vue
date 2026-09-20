<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbavqlbef"/><path class="plsh0ebyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yamaps" /></template>
<style>
.jbavqlbef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.93 4.25a12 12 0 1 0 12.13 11.9a12 12 0 0 0-12.13-11.9m0 7.43a4.57 4.57 0 0 1 4.61 4.52A4.59 4.59 0 1 1 24 11.68Z");
}

.plsh0ebyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.82 18.66C33.45 27.32 27 34 21.46 43.25l3.05-15");
}

</style>
