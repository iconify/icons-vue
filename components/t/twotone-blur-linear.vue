<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scc8fhexp"/><circle class="o_u96ibiu"/><circle class="sp1gjrk1i"/><circle class="qrvm5rl5b"/><path class="unk05l42p"/><circle class="aythhbbwf"/><path class="ejsolib7l"/><circle class="p5306tnxy"/><circle class="if4mi8b5v"/><circle class="ep32kedqn"/><path class="sn4_2-bwe"/><circle class="y8mkib1ak"/><circle class="eqzj32bze"/><path class="a1a9cxoke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-blur-linear" /></template>
<style>
.a1a9cxoke {
  fill: currentColor;
  d: path("M3 19h18v2H3z");
}

.aythhbbwf {
  cx: 13px;
  cy: 12px;
  r: 1px;
  fill: currentColor;
}

.ejsolib7l {
  fill: currentColor;
  d: path("M3 3h18v2H3z");
}

.ep32kedqn {
  cx: 5px;
  cy: 16px;
  r: 1.5px;
  fill: currentColor;
}

.eqzj32bze {
  cx: 9px;
  cy: 8px;
  r: 1px;
  fill: currentColor;
}

.if4mi8b5v {
  cx: 5px;
  cy: 12px;
  r: 1.5px;
  fill: currentColor;
}

.o_u96ibiu {
  cx: 9px;
  cy: 12px;
  r: 1px;
  fill: currentColor;
}

.p5306tnxy {
  cx: 5px;
  cy: 8px;
  r: 1.5px;
  fill: currentColor;
}

.qrvm5rl5b {
  cx: 13px;
  cy: 16px;
  r: 1px;
  fill: currentColor;
}

.scc8fhexp {
  fill: currentColor;
  d: path("M17 16.5c.28 0 .5-.22.5-.5s-.22-.5-.5-.5s-.5.22-.5.5s.22.5.5.5");
}

.sn4_2-bwe {
  fill: currentColor;
  d: path("M17 8.5c.28 0 .5-.22.5-.5s-.22-.5-.5-.5s-.5.22-.5.5s.22.5.5.5");
}

.sp1gjrk1i {
  cx: 13px;
  cy: 8px;
  r: 1px;
  fill: currentColor;
}

.unk05l42p {
  fill: currentColor;
  d: path("M17 12.5c.28 0 .5-.22.5-.5s-.22-.5-.5-.5s-.5.22-.5.5s.22.5.5.5");
}

.y8mkib1ak {
  cx: 9px;
  cy: 16px;
  r: 1px;
  fill: currentColor;
}

</style>
