<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uobt8w6ar"/><path class="bp5a5jbne"/><path class="pqqa7bbrw"/><path class="ue1ek8n-x"/><path class="cg46ktbtw"/><path class="rx_xvr3sr"/><circle class="fjnniaclu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reproductor-nacional" /></template>
<style>
.bp5a5jbne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.17 19.175h16.45c1.173 0 2.123 1.018 2.123 2.274v13.08c0 1.257-.95 2.275-2.122 2.275H13.17c-1.173 0-2.123-1.018-2.123-2.275V21.45c0-1.256.95-2.275 2.122-2.275");
}

.cg46ktbtw {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M34.774 22.143a1.508 1.508 0 1 1-.009.028m.009 5.399a1.508 1.508 0 1 1-.009.027m.009 5.398a1.508 1.508 0 1 1-.009.029");
}

.fjnniaclu {
  cx: 22.626px;
  cy: 14.81px;
  r: 1.612px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.pqqa7bbrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.477 27.782h8.599v-8.607m11.197 8.607h-11.09");
}

.rx_xvr3sr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.13 5.5l-9.09 8.58M12.085 40.436L10.919 42.5h4.261l-1.108-2.032m19.718-.032L32.624 42.5h4.261l-1.108-2.032");
}

.ue1ek8n-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.935 26.253l-1.719-1.148l-1.92.765l.56-1.99l-1.32-1.589l2.065-.082l1.103-1.747l.716 1.939l2.003.51l-1.622 1.28zM21.41 13.76L12.66 5.5");
}

.uobt8w6ar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.66h12.38c1.76 0 3.19 1.43 3.19 3.19v18.37a3.2 3.2 0 0 1-3.19 3.2H11.62a3.2 3.2 0 0 1-3.19-3.2V18.85c0-1.76 1.43-3.19 3.19-3.19h9.64");
}

</style>
