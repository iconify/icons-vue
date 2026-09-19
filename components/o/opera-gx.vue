<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="i3n4lrb0n"/><path class="j6gsinc7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opera-gx" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i3n4lrb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.519 5.16A18.84 18.84 0 0 0 12.68 24h0a18.647 18.647 0 0 0 22.185 18.501A21.45 21.45 0 0 0 34.9 5.473a19 19 0 0 0-3.38-.312Z");
}

.j6gsinc7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.624 9.362a18.842 18.842 0 0 1-.012 29.286");
}

</style>
