<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="vl9ccf35h"/><circle class="lvglgcbfx"/><ellipse class="juq8qcctg"/><ellipse class="g-50rh96c"/><path class="w40t30bft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartq" /></template>
<style>
.g-50rh96c {
  cx: 32.634px;
  cy: 17.219px;
  rx: 6.044px;
  ry: 4.317px;
}

.juq8qcctg {
  cx: 15.366px;
  cy: 17.219px;
  rx: 6.044px;
  ry: 4.317px;
}

.lvglgcbfx {
  cx: 24px;
  cy: 21.904px;
  r: 16.404px;
}

.vl9ccf35h {
  d: path("m38.856 38.743l-5.535-2.634m-6.917-18.821l-4.905.026");
}

.w40t30bft {
  d: path("m25.669 39.047l6.907-1.727v5.18zm-3.337 0l-6.908-1.727v5.18z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
