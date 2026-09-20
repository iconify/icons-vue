<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><g class="y9tr6bcfx"><path class="y8iyz033h"/><path class="twv0eqn-v"/></g><circle class="vj1cecdxx"/><path class="eamq_7v5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toing" /></template>
<style>
.eamq_7v5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.574 20.762l1.073 5.19m-12.031-4.61l1.205 5.827a1 1 0 0 0 1.182.777l.293-.061m-3.374-4.715l2.057-.425m17.4 1.815l-.668-3.23a2 2 0 0 0-3.917.81m.667 3.231l-1.072-5.191m-9.142 3.932a2 2 0 1 1 3.917-.81l.263 1.273a2 2 0 1 1-3.917.81z");
}

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

.twv0eqn-v {
  d: path("M34.936 23.518za2 2 0 0 1-2.364-1.554l-.263-1.273a2 2 0 1 1 3.917-.81l.264 1.273a2 2 0 0 1-1.554 2.364");
}

.vj1cecdxx {
  cx: 22.078px;
  cy: 18.363px;
  r: 0.7px;
  fill: currentColor;
}

.y8iyz033h {
  d: path("m35.822 17.923l1.214 5.875a2 2 0 0 1-1.554 2.364c-.54.111-22.104 4.22-21.94 4.175");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
