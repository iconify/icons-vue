<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="k3okqnbic"/><path class="qfo5gq_iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-audiobook-player" /></template>
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

.k3okqnbic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.274 24v18.182m-18.548 2.055v-9.279a2 2 0 0 1 1.12-1.796l16.868-8.264a1 1 0 0 0 0-1.796l-17.988-8.813");
}

.qfo5gq_iy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.347 23.633l-10.224-4.42a1 1 0 0 0-1.397.919v7.736a1 1 0 0 0 1.397.918l10.224-4.419a.4.4 0 0 0 0-.734");
}

</style>
