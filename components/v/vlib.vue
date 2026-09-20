<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="e_oryxyrc"/><circle class="ouvzq2bfm"/><path class="od_oezpwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vlib" /></template>
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

.e_oryxyrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.01 34.798l-.913 4.953l-2.588-4.321m9.144.821a1.778 1.778 0 0 1-3.407.457l-.442-1.067a1.778 1.778 0 1 1 3.286-1.36l.22.533l-3.285 1.36m2.62-6.274l3.606 5.073a.89.89 0 0 0 1.24.21l.217-.155");
}

.od_oezpwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.428 29.51l3.034 3.605m.395-4.326a1.778 1.778 0 1 1 2.169-2.819l.916.705a1.778 1.778 0 1 1-2.169 2.819m1.41 1.084l-5.637-4.337m3.33-2.66l-.236-1.301m-7.872 19.384l11.839-8.726");
}

.ouvzq2bfm {
  cx: 31.325px;
  cy: 28.073px;
  r: 0.75px;
  fill: currentColor;
}

</style>
