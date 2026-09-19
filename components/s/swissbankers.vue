<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qw3xuwahg"/><circle class="e6g5ev1ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swissbankers" /></template>
<style>
.e6g5ev1ue {
  cx: 39.145px;
  cy: 13.79px;
  r: 4.355px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qw3xuwahg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.145 38.565l-11.549-20.42l-11.548 20.42L4.5 18.145");
}

</style>
