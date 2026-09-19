<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e5str-bzo"/><path class="auqyvlbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:takeflite-go" /></template>
<style>
.auqyvlbry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.625 6.74a9.25 9.25 0 1 1-1.916 14.55M24 14.75a9.25 9.25 0 0 1 2.164-5.946M14.75 24a9.25 9.25 0 1 1-9.25 9.25");
}

.e5str-bzo {
  cx: 14.75px;
  cy: 14.75px;
  r: 9.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
