<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="kz5yf3b0u"/><path class="onp4ozbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:synology-assistant" /></template>
<style>
.kz5yf3b0u {
  width: 37px;
  height: 33.172px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.252px;
}

.onp4ozbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.828 5.5v33.172m5.762-26.447h3.148m-3.148 5.08h3.148M8.129 38.672h5.103V42.5H8.129zm26.74 0h5.103V42.5h-5.103z");
}

</style>
