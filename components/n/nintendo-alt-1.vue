<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="fqxo3yb_r"/><path class="obbgo4-6v"/><circle class="s-689abfm"/><path class="flgkcibxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nintendo-alt-1" /></template>
<style>
.flgkcibxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.204 23.569v3.222m6.699-4.458v4.458m-.787-3.222h1.574m8.715 3.222v-1.723a1.499 1.499 0 1 0-2.997 0m-.001 1.723v-3.222m-8.487 3.222v-1.723a1.499 1.499 0 1 0-2.997 0m0 1.723v-3.222m9.307 2.945a1.499 1.499 0 0 1-2.368-1.221v-.225a1.499 1.499 0 1 1 2.997 0v.112h-2.996m12.1-.112a1.499 1.499 0 1 0-2.997 0v.225a1.499 1.499 0 0 0 2.997 0m0 1.498v-5.245m1.54 3.522a1.499 1.499 0 0 1 2.997 0v.225a1.499 1.499 0 0 1-2.997 0z");
}

.fqxo3yb_r {
  width: 41px;
  height: 10px;
  x: 3.5px;
  y: 19.18px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
  ry: 5px;
}

.obbgo4-6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 26.791v-5.245l3.972 5.245v-5.245");
}

.s-689abfm {
  cx: 14.204px;
  cy: 21.733px;
  r: 0.75px;
  fill: currentColor;
}

</style>
