<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c2xrbabwq"/><path class="nhgxnrw9l"/><circle class="wu9hwsblh"/><path class="fjcne632k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skrill" /></template>
<style>
.c2xrbabwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

.fjcne632k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.556 22.654v6.634M9.698 28.191c.614.8 1.384 1.097 2.455 1.097h1.483a2.5 2.5 0 0 0 2.498-2.503h0a2.5 2.5 0 0 0-2.498-2.503h-1.638A2.5 2.5 0 0 1 9.5 21.779h0a2.5 2.5 0 0 1 2.498-2.504h1.482c1.071 0 1.841.298 2.455 1.097m17.218-1.097v8.762c0 .69.56 1.251 1.252 1.251h.375m2.093-10.013v8.762c0 .69.56 1.251 1.252 1.251h.375");
}

.nhgxnrw9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.784 29.288v-4.13a2.503 2.503 0 0 1 2.503-2.503h0m-9.907-3.38v10.013m.001-2.127l4.533-4.51m-3.09 3.075l3.563 3.547");
}

.wu9hwsblh {
  cx: 30.556px;
  cy: 19.588px;
  r: 0.75px;
  fill: currentColor;
}

</style>
