<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="lhf9rxffb"/><path class="ltklkx1ml"/><path class="dmx5rnn0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:windyapp" /></template>
<style>
.dmx5rnn0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 24l-5.514-8.194a9.9 9.9 0 0 1 3.6-1.495M24 24l-9.02-1.689a8.9 8.9 0 0 1 1.401-3.456zm-11.478 7.772l-3.595 2.431a18.2 18.2 0 0 1-2.738-6.452l2.412-.508a15.7 15.7 0 0 1-.069-6.139l6.447 1.207M24 2.5v4.844M8.264 24H2.5m43 0h-8.922M14.2 33.8l-5.403 5.403M39.203 8.797l-2.229 2.229M24 33.53V45.5m-6.738-28.238L8.797 8.797m30.406 30.406l-8.465-8.465");
}

.lhf9rxffb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.467 21.098a15.7 15.7 0 0 0-2.28-5.687l2.065-1.345a18.2 18.2 0 0 0-5.298-5.305L24 24zM12.522 31.772a13.9 13.9 0 0 0 3.881 3.823l-1.027 1.568a15.7 15.7 0 0 0 5.701 2.3L24 24z");
}

.ltklkx1ml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.363 21.68a12.6 12.6 0 0 1-.036 4.824l-1.698-.344a10.9 10.9 0 0 1-1.664 3.945L24 24m0 0L20.77 7.66a16.7 16.7 0 0 1 6.598.028l-.186.9a15.7 15.7 0 0 1 5.423 2.236M24 24l3.855 5.87a7 7 0 0 1-2.688 1.055z");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
