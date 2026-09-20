<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t89oaccyi"/><path class="wmp0rws_u"/><circle class="gbsbu-b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wezone" /></template>
<style>
.gbsbu-b1n {
  cx: 35.28px;
  cy: 21.619px;
  r: 3.501px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t89oaccyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 34.265V20.797a8.5 8.5 0 0 1 4.321-7.4l3.13-1.766a7.27 7.27 0 0 1 7.203.03l7.062 4.064c4.15 2.387 4.204 8.356.099 10.818L9.1 36.872c-2.024 1.214-4.6-.245-4.6-2.607m8.22-9.145v-7.002m-3.501 3.501h7.002");
}

.wmp0rws_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 34.265V20.797a8.5 8.5 0 0 0-4.321-7.4l-3.13-1.766a7.27 7.27 0 0 0-7.203.03l-7.062 4.064c-4.15 2.387-4.204 8.356-.098 10.818l17.213 10.328c2.025 1.215 4.601-.244 4.601-2.606");
}

</style>
