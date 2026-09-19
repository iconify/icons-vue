<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fwf4y0fym"/><rect transform="rotate(-43.49 12.482 35.64)" class="n076al-cf"/><path class="hny8zni9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:podaura" /></template>
<style>
.fwf4y0fym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.762 5.5v4.622m9.319-.243l-3.254 3.402m7.511 6.028H37.66M15.905 32.393l4.94-5.313v-5.236m0 5.236l5.23.074");
}

.hny8zni9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.85 28.77a11.616 11.616 0 1 1 20.938 2.45a11.616 11.616 0 0 1-13.508 4.97M8.485 31.428l7.994 8.425M6.887 36.6c-1.372 2.877 1.352 5.912 4.283 4.513");
}

.n076al-cf {
  width: 9.437px;
  height: 11.615px;
  x: 7.763px;
  y: 29.833px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.452px;
  ry: 1.452px;
}

</style>
