<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="es8vy_bnp"/><circle class="uh63l0_7q"/><path class="qx6c8ccfs"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:persian-calendar" /></template>
<style>
.es8vy_bnp {
  cx: 32.5px;
  cy: 11px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.qx6c8ccfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 35.299V20.701m8.95-.001v5.252a3 3 0 0 1-3 3H13.5M29.693 20.7H34.5v10.283h-4.807c-1.656 0-3-1.344-3-3v-4.282c0-1.656 1.344-3 3-3M34.5 35.299v-4.316");
}

.uh63l0_7q {
  cx: 15.5px;
  cy: 11px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
