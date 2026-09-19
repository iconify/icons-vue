<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="knob1cbkb"/><rect class="j3s9ivbxi"/><circle class="fcw-yesds"/><circle class="oezfhmlut"/><circle class="kl4omd2ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:seqtrak" /></template>
<style>
.fcw-yesds {
  cx: 35.75px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
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

.kl4omd2ly {
  cx: 35.75px;
  cy: 30.5px;
  r: 0.75px;
  fill: currentColor;
}

.knob1cbkb {
  cx: 24px;
  cy: 24px;
  r: 7.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oezfhmlut {
  cx: 35.75px;
  cy: 17.5px;
  r: 0.75px;
  fill: currentColor;
}

</style>
