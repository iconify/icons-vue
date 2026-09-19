<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="usa9qmbta"/><path class="lxdugg5lc"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moorepay" /></template>
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

.lxdugg5lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.842 22.83a3.17 3.17 0 0 1 3.17-3.172h0a3.17 3.17 0 0 1 3.172 3.171v5.232m1.974-3.171a3.17 3.17 0 0 0 3.171 3.171h0a3.17 3.17 0 0 0 3.171-3.17v-2.062a3.17 3.17 0 0 0-3.17-3.17h0a3.17 3.17 0 0 0-3.172 3.17m0 0v9.513");
}

.usa9qmbta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 28.061V22.83a3.17 3.17 0 0 1 3.17-3.17h0a3.17 3.17 0 0 1 3.172 3.17v5.232");
}

</style>
