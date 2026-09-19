<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="deq40oavd"/><circle class="ongcg6byx"/><path class="jhfc_3b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mooltifill" /></template>
<style>
.deq40oavd {
  width: 29.135px;
  height: 25.056px;
  x: 9.432px;
  y: 18.444px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.jhfc_3b-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.26 13.24A8.74 8.74 0 0 1 24 4.5h0a8.74 8.74 0 0 1 8.74 8.74m0 0v5.204M15.26 13.24l.01 5.204m-.01-5.204v5.204");
}

.ongcg6byx {
  cx: 24px;
  cy: 30.973px;
  r: 3.496px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
