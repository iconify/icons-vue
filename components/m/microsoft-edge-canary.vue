<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tjs4g1b7x"/><path class="cnms0g_9c"/><path class="q7vu1mbfs"/><circle class="kg5q9ub6a"/><path class="i5gv1xbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-edge-canary" /></template>
<style>
.cnms0g_9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.445 4.663a21.5 21.5 0 1 0-9.44 40.837c7.985 0 14.612-4.581 18.684-10.82c.66-.998-.509-1.996-1.557-1.077a15.5 15.5 0 0 1-7.755 2.814c-4.202 0-14.712-2.814-14.712-11.977c0-3.803 2.157-4.78 2.157-4.78");
}

.i5gv1xbce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.15 10.817v.033a2.65 2.65 0 0 1-2.65 2.65h0a2.65 2.65 0 0 1-2.65-2.65v-2.7A2.65 2.65 0 0 1 38.5 5.5h0a2.65 2.65 0 0 1 2.65 2.65v.033");
}

.kg5q9ub6a {
  cx: 38.5px;
  cy: 9.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q7vu1mbfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.545 24.04c0-7.275 7.826-11.358 13.844-11.358s13.105 4.771 13.105 11.359c0 3.194-1.916 2.765-1.916 4.68c0 1.488 2.994 2.496 6.348 2.496c5.43 0 11.977-2.715 11.508-9.372h0a21.5 21.5 0 0 0-2.08-7.308");
}

.tjs4g1b7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.78 45.33c-7.357-.08-12.757-7.605-12.757-13.434c0-7.287 5.99-13.245 9.982-13.245c4.451 0 5.43 4.78 5.43 4.78");
}

</style>
