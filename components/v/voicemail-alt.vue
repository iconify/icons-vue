<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ryj6p1iuz"/><circle class="qt67y024j"/><path class="l0qftmbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:voicemail-alt" /></template>
<style>
.l0qftmbyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.945 33.95l19.7-3.47m-26.8-10.875V9.5c0-2.216 1.784-4 4-4h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-6.625");
}

.qt67y024j {
  cx: 32.195px;
  cy: 22.26px;
  r: 8.34px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ryj6p1iuz {
  cx: 12.495px;
  cy: 25.74px;
  r: 8.34px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
