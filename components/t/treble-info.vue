<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zvmzeo_nw"/><path class="maw78pojq"/><circle class="nv37re0_w"/><path class="ns8k5lbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:treble-info" /></template>
<style>
.maw78pojq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15 9.5h18v29H15z");
}

.ns8k5lbrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 22.177v8.035");
}

.nv37re0_w {
  cx: 24px;
  cy: 18.538px;
  r: 0.75px;
  fill: currentColor;
}

.zvmzeo_nw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34 4.5H14a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h20a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2");
}

</style>
