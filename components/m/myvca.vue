<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="t_bo5btxg"/><path class="jeh3b_46j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myvca" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.jeh3b_46j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.35 21.717v2.843c0 .952-.772 1.724-1.724 1.724h0a1.723 1.723 0 0 1-1.723-1.724v-2.843M9.298 23.44c0-.952.771-1.723 1.723-1.723h0c.952 0 1.723.771 1.723 1.723v2.844m-3.446-4.568v4.568m3.447-2.844c0-.952.771-1.723 1.723-1.723h0c.952 0 1.723.771 1.723 1.723v2.844m10.847-6.894l-2.284 6.894l-2.283-6.894m10.427 4.582V24a2.284 2.284 0 0 1-2.284 2.284h0A2.284 2.284 0 0 1 28.331 24v-2.327a2.284 2.284 0 0 1 2.283-2.283h0a2.284 2.284 0 0 1 2.284 2.283v.029M37.946 24h-3.054m-.757 2.284l2.284-6.894l2.283 6.894");
}

.t_bo5btxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.35 24.56v2.327c0 .952-.772 1.723-1.724 1.723h0c-.476 0-.906-.193-1.218-.505");
}

</style>
