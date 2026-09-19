<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jmod4gbie"/><path class="gc636bbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nebulo" /></template>
<style>
.gc636bbnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.86 26.77h9.8m-3.28 2.85v-2.85m-10.11-9.09h-6.22a9.56 9.56 0 0 0 0 19.11h21.2a8.25 8.25 0 0 0 0-16.5h-.2a10.81 10.81 0 0 0-20.57-2.6");
}

.jmod4gbie {
  cx: 20.27px;
  cy: 26.77px;
  r: 3.59px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
