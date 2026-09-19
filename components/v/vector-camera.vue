<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="o2jezvhfr"/><circle class="qtoncebpf"/><path class="eq6b8eb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vector-camera" /></template>
<style>
.eq6b8eb8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.5 12.142h-8.457L31.2 7.992a1 1 0 0 0-.914-.593h-12.57a1 1 0 0 0-.914.594l-1.844 4.149H6.5a2 2 0 0 0-2 2v24.46a2 2 0 0 0 2 2h35a2 2 0 0 0 2-2v-24.46a2 2 0 0 0-2-2");
}

.o2jezvhfr {
  cx: 24px;
  cy: 26.372px;
  r: 10.014px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qtoncebpf {
  cx: 24px;
  cy: 26.372px;
  r: 6.324px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
