<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="emkkxxpdm"/><path class="v-y7_b0tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moonshine" /></template>
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

.emkkxxpdm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.407 25.949l-5.255-11.556l-12.19 13.489l1.919 4.217l8.771-9.706l3.337 7.338z");
}

.v-y7_b0tn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.1 22.196l-3.548-7.802l-12.19 13.489l1.919 4.217l8.771-9.706l1.63 3.585");
}

</style>
