<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d4b_odr9v"/><path class="nmhbracdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ted" /></template>
<style>
.d4b_odr9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M20.811 30.226h6.226m-6.226-12.452h6.226M20.811 24h4.059m-4.059-6.226v12.452");
}

.nmhbracdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.25 30.226V17.774h2.802a5.45 5.45 0 0 1 5.448 5.448v1.556a5.45 5.45 0 0 1-5.448 5.448zM9.5 17.774h8.25m-4.125 12.452V17.774");
}

</style>
