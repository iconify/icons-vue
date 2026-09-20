<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="nq9ppfbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qbittorrent-remote" /></template>
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

.nq9ppfbul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.651 22.364a5.034 5.034 0 1 1 10.069 0v3.272a5.034 5.034 0 1 1-10.069 0m0 5.035V10.533m-5.302 15.103a5.034 5.034 0 1 1-10.069 0v-3.272a5.034 5.034 0 1 1 10.069 0m0-5.035v20.138");
}

</style>
