<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="sg8ehwcrb"/><rect class="yu0n5sbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:number-circle-10" /></template>
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

.sg8ehwcrb {
  d: path("m14.368 18.178l4-2.178v16m14.01-14.116l-8.104 12.232");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yu0n5sbsa {
  width: 10.6px;
  height: 16px;
  x: 23.032px;
  y: 16px;
  rx: 5.3px;
  ry: 5.3px;
}

</style>
