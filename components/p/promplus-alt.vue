<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xf_n6bbon"/><path class="fupfcpbpv"/><path class="i3untb0kt"/><circle class="g5jcv-tgq"/><path class="nyzjuko5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:promplus-alt" /></template>
<style>
.fupfcpbpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.797 27.8c0-1-1-1.2-1.6-1c-1.3.4-1 2.8-1.8 3.6c-1 1-3 .9-4.6.9s-3.6.2-4.6-.9c-.8-.8-.5-3.3-1.8-3.6c-.6-.2-1.7 0-1.6 1c.3 6.1 4.7 5.7 8 5.7s7.8.4 8-5.7m-11.2-12.7h2.1v2.1h-2.1zm4.2 0h2.1v2.1h-2.1zm6.2 10.9c.3-2.1.8-5.8 1-7.8c.1-.7-1-2.2-2.5-2.2h-2.2m-10.7 10c-.3-2.1-.8-5.8-1-7.8c-.2-.7 1-2.2 2.5-2.2h2.2");
}

.g5jcv-tgq {
  cx: 10.397px;
  cy: 27.9px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i3untb0kt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.197 25.9v2.7h3.3v-2.7h2.7v-3.3h-2.7v-2.7h-3.3v2.7h-2.7v3.3zm-23.8 5.9c-1.5-.8-2.4-2.3-2.4-3.9c0-2.4 2-4.4 4.4-4.4h0c2.4 0 4.4 2 4.4 4.4h0c0 1.6-.9 3.2-2.4 3.9");
}

.nyzjuko5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.297 33.5c-1.2 5.2-5.8 9-11.3 9c-6.4 0-11.6-5.3-11.6-11.8v-.8");
}

.xf_n6bbon {
  cx: 33.797px;
  cy: 9.6px;
  r: 4.1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
