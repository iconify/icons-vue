<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="kj0szibax"/><path class="nybxy-6ur"/><path class="voe_pqv-d"/></g><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zood-location" /></template>
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

.kj0szibax {
  d: path("M23.955 30.007s-11.038-10.207.252-12.014c0 0 10.673 1.405-.252 12.014");
}

.nybxy-6ur {
  d: path("M14.763 4.784s25.583 2.029 27.943 29.61M4.92 14.261S5.911 39.5 34.162 42.94");
}

.voe_pqv-d {
  d: path("M4.814 33.535s.06-24.951 28.112-28.916M14.28 43.094s25.87-.627 28.684-28.714");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
