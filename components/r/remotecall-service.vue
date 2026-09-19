<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rf14rdbjp"/><path class="xqgs-6bdv"/><rect transform="rotate(-41.23 29.381 28.43)" class="v4poswb0p"/><path class="davn7bb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:remotecall-service" /></template>
<style>
.davn7bb2i {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m25.49 24.244l2.054 2.133m3.336-5.198v-10.2c0-3.58-2.84-6.48-6.348-6.48h-7.8c-3.508 0-6.35 2.9-6.35 6.48v26.04c0 3.58 2.842 6.48 6.35 6.48h7.8c3.508 0 6.349-2.9 6.349-6.48v-.083");
}

.rf14rdbjp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M18.05 26.885c-.06-2.763.964-5.417 2.83-7.334s4.41-2.924 7.023-2.783");
}

.v4poswb0p {
  width: 11.935px;
  height: 18.818px;
  x: 23.414px;
  y: 19.021px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 5.968px;
  ry: 5.968px;
}

.xqgs-6bdv {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M14.954 26.7a12.36 12.36 0 0 1 3.675-9.108a12.1 12.1 0 0 1 9.115-3.456");
}

</style>
