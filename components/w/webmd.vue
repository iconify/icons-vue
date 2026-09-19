<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bucud4b0c"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:webmd" /></template>
<style>
.bucud4b0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.553 37.487V25.878l5.81 11.622l5.812-11.604V37.5m2.869-.09V25.787h2.615a5.085 5.085 0 0 1 5.085 5.085v1.453a5.085 5.085 0 0 1-5.085 5.085zm4.461-19.814c.486-1.605 2.181-2.905 3.786-2.905s2.511 1.3 2.025 2.905l-.572 1.889c-.486 1.604-2.18 2.905-3.785 2.905s-2.512-1.3-2.026-2.905m-.88 2.905l3.52-11.622M23.79 10.5l-6.426 11.622l.614-11.622l-6.426 11.622l.615-11.622m15.012 10.314c-.766.876-1.888 1.467-2.969 1.467c-1.605 0-2.512-1.301-2.025-2.906l.572-1.889c.486-1.604 2.18-2.905 3.785-2.905s2.512 1.3 2.026 2.906l-.286.944H22.47");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
