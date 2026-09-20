<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oc58d8bnr"/><path class="dxx0-ftqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:recorder" /></template>
<style>
.dxx0-ftqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.23 23.79a12 12 0 0 0 23.54 0");
}

.oc58d8bnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5za7.61 7.61 0 0 1 7.61 7.61v9.42A7.61 7.61 0 0 1 24 29.14a7.61 7.61 0 0 1-7.61-7.61v-9.42A7.61 7.61 0 0 1 24 4.5m2.94 28.65v9.71a.64.64 0 0 1-.63.64h-4.62a.64.64 0 0 1-.63-.64v-9.71");
}

</style>
