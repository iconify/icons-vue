<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kw42l6_rw"/><path class="k-pm4fwmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:postfinance" /></template>
<style>
.k-pm4fwmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4z");
}

.kw42l6_rw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.9 24h4.9m-19 7.5l3.2-15h4.9c2.8 0 4.6 2.2 4 5.1c-.6 2.8-3.3 5.1-6.1 5.1h-4.9m11.4 4.8l3.2-15H37");
}

</style>
