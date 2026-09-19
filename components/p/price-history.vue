<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jkg5cibxt"/><circle class="pd_s63bbe"/><path class="k-pm4fwmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:price-history" /></template>
<style>
.jkg5cibxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.2 20.4v2.8m29.6-1.6v2.9m-8.5-.9v7.3m-4.2-4.8v9.1m-4.2-12.6v8.5m-4.2-10.7v7m-4.3-10.3v6.8m21.2-2.3v6");
}

.k-pm4fwmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4z");
}

.pd_s63bbe {
  cx: 26.1px;
  cy: 35.2px;
  r: 0.8px;
  fill: currentColor;
}

</style>
