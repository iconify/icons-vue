<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="z5_iuibim"/><circle class="lr4o40xhp"/><circle class="yhzr9bcri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:resplash" /></template>
<style>
.lr4o40xhp {
  cx: 32.878px;
  cy: 24px;
  r: 10.622px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yhzr9bcri {
  cx: 10.623px;
  cy: 24.3px;
  r: 2.12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z5_iuibim {
  cx: 10.623px;
  cy: 24.3px;
  r: 6.123px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
