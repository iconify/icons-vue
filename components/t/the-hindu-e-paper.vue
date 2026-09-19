<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7-wn9b5o"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-hindu-e-paper" /></template>
<style>
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

.l7-wn9b5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 20.94h29m-29 5.12h29M20.276 15.82H38.5M20.276 10.7H38.5m-29 20.48h29m-29 5.12h29m-29-25.6h3.386m-1.693 5.11V10.7m3.609.01v5.11m3.385-5.11v5.11m-3.385-2.565h3.385");
}

</style>
