<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7by_bb1m"/><path class="vj-dqm-nt"/><circle class="i_yebpbox"/><path class="q6l3nebmb"/><circle class="o_msmvslt"/><path class="yen3lmb8j"/><circle class="we5sl5bnl"/><path class="r268_vbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:videlibri" /></template>
<style>
.i_yebpbox {
  cx: 23.785px;
  cy: 14.563px;
  r: 0.7px;
  fill: currentColor;
}

.l7by_bb1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.726 4.5H10.4a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h2.326m0-39v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2z");
}

.o_msmvslt {
  cx: 22.742px;
  cy: 26.387px;
  r: 0.7px;
  fill: currentColor;
}

.q6l3nebmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.785 17.013v5.3m11.61-1.027a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4m-1.925-.633a2 2 0 1 0-4 0v1.3a2 2 0 1 0 4 0m0 2v-8M16.839 26.137v8h4m9.969-3.3a2 2 0 0 1 2-2m-2 0v5.3");
}

.r268_vbla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.742 28.837v5.3m-9.915-3.3a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0m0 2v-8");
}

.vj-dqm-nt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.924 14.313l-2.65 8l-2.65-8");
}

.we5sl5bnl {
  cx: 34.742px;
  cy: 26.387px;
  r: 0.7px;
  fill: currentColor;
}

.yen3lmb8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.742 28.837v5.3");
}

</style>
