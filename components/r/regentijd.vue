<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vves2owfl"/><path class="kif4gbw3k"/><path class="drtutl8cg"/><path class="q110tl-ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:regentijd" /></template>
<style>
.drtutl8cg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.551 41.336a6.77 6.77 0 1 0-9.574-9.574m9.574-19.149l.979-.98M17.402 22.187c12.104-12.104 19.15-9.574 19.15-9.574");
}

.kif4gbw3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.402 22.187a6.77 6.77 0 0 0-9.574-9.574m19.149 19.149a6.77 6.77 0 0 0-9.575-9.575");
}

.q110tl-ns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.977 31.762c12.104-12.104 9.574-19.15 9.574-19.15m-9.574 9.575l-12.35 12.35a5.347 5.347 0 0 1-7.56 0h0a5.347 5.347 0 0 1 0-7.563l.897-.897");
}

.vves2owfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.551 41.336A20.31 20.31 0 0 0 7.828 12.613");
}

</style>
