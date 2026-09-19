<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="mhwy4k0kl"/><circle class="k99s77btx"/><path class="y1sf5cbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oversec" /></template>
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

.k99s77btx {
  cx: 32.75px;
  cy: 17.78px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mhwy4k0kl {
  cx: 15.25px;
  cy: 17.78px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y1sf5cbcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.84 29l6.24-3.6l2.08 3.6L28 31.36l4.16 2.41l-2.08 3.6l-6.24-3.6l-6.24 3.6l-2.08-3.6l4.16-2.41L15.52 29l2.08-3.6Z");
}

</style>
