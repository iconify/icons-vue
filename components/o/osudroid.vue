<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="azlbvwjfn"/><path class="tz3v5nbgu"/><rect class="a4taf5bqi"/><path class="k6mvlouvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:osudroid" /></template>
<style>
.a4taf5bqi {
  width: 5.28px;
  height: 7px;
  x: 13.71px;
  y: 31.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.64px;
}

.azlbvwjfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.51 28.31V40a1.94 1.94 0 0 0 1.94 2h33.1a2 2 0 0 0 2-2V28.31");
}

.k6mvlouvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29 31.65V36a2.64 2.64 0 0 0 2.64 2.64h0A2.65 2.65 0 0 0 34.29 36v-4.35m-12.54 6.41a3 3 0 0 0 2.17.59h.6a1.75 1.75 0 0 0 1.74-1.75h0a1.74 1.74 0 0 0-1.74-1.75h-1.19a1.76 1.76 0 0 1-1.75-1.75h0a1.75 1.75 0 0 1 1.75-1.75h.59a3 3 0 0 1 2.18.59");
}

.tz3v5nbgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39 13.72l2.58-2.56a3 3 0 0 0-4.27-4.26h0l-2.55 2.6a18.39 18.39 0 0 0-21.51 0l-2.57-2.57A3.22 3.22 0 0 0 8.5 6a3 3 0 0 0-2.12 5.15L9 13.71a18.4 18.4 0 0 0-3.47 10.8v3.8h37v-3.8A18.57 18.57 0 0 0 39 13.72m-19.87 7a2.93 2.93 0 1 1-2.93-2.92a2.93 2.93 0 0 1 2.94 2.9Zm12.65 2.92a2.92 2.92 0 1 1 2.92-2.92a2.92 2.92 0 0 1-2.91 2.9Z");
}

</style>
