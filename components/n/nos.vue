<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u43xikbaj"/><path class="tmz9clp-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nos" /></template>
<style>
.tmz9clp-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.51 21.51 0 0 0 2.5 24A21.51 21.51 0 0 0 24 45.5a21.5 21.5 0 0 0 0-43");
}

.u43xikbaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.51 19a5 5 0 1 0 5 5a5 5 0 0 0-5-5M9 28.82v-9.6l7.39 9.6v-9.6m15.92 8.69A2.76 2.76 0 0 0 34.74 29h1.78A2.48 2.48 0 0 0 39 26.51A2.48 2.48 0 0 0 36.52 24h-1.93a2.48 2.48 0 0 1-2.48-2.48a2.48 2.48 0 0 1 2.48-2.48h1.78a2.76 2.76 0 0 1 2.43 1.09");
}

</style>
