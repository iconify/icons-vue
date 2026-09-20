<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q1jd-cjol"/><circle class="cpk0fnbgt"/><path class="rce72-b2t"/><path class="ptmpgwbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tisseo" /></template>
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

.ptmpgwbxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.22 23.86h.61a1.78 1.78 0 0 1 1.77 1.78a1.78 1.78 0 0 1-1.77 1.78m1.6-6.52a3 3 0 0 0-2.21-.6h-.6M19 26.82a3 3 0 0 0 2.21.6h.61m5.49-7.12a1.78 1.78 0 0 0-1.78 1.78a1.78 1.78 0 0 0 1.78 1.78h.6m0 0h.6a1.78 1.78 0 0 1 1.78 1.78a1.78 1.78 0 0 1-1.78 1.78m1.61-6.52a3 3 0 0 0-2.21-.6h-.6m-1.61 6.52a3 3 0 0 0 2.21.6h.6");
}

.q1jd-cjol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.34 27.42h3.56m-3.56-7.12h3.56m-1.78 0v7.12m17.1 0h3.56m-3.56-7.12h3.56m-3.56 3.56h2.32m-2.32-3.56v7.12M42 22.68a2.39 2.39 0 0 0-2.52-2.39a2.48 2.48 0 0 0-2.26 2.52V25a2.39 2.39 0 0 0 2.39 2.39A2.39 2.39 0 0 0 42 25zM6.04 20.29h5.38m-2.69 7.13v-7.13m24.44-1.78l1.66-.78");
}

.rce72-b2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.62 20.3a1.78 1.78 0 0 0-1.78 1.78a1.78 1.78 0 0 0 1.78 1.78h.6");
}

</style>
