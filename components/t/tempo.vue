<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sqvvb3xug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tempo" /></template>
<style>
.sqvvb3xug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 12.88l.028 7.616M43.08 12.88l.029 7.616M39.25 7.264v19.07M8.334 7.264v19.07m27.024-16.262v13.343M12.205 10.072v13.343m19.303-10.508v10.036M16.077 12.907v10.036m11.65-12.76v25.909m-7.778-25.909v25.909M23.82 7.208v35.584");
}

</style>
