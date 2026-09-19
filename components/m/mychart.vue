<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o2xprcc6o"/><path class="g2j6tjbww"/><path class="m0a-k3bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mychart" /></template>
<style>
.g2j6tjbww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.295h-39v18.72a2.18 2.18 0 0 0 2.16 2.2h34.66a2.18 2.18 0 0 0 2.18-2.18v-.02h0Z");
}

.m0a-k3bhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.215 23.3a3.57 3.57 0 0 0-2.275 6.085l5.06 5.05l5.06-5.05A3.574 3.574 0 0 0 24 24.337a3.582 3.582 0 0 0-2.785-1.037Z");
}

.o2xprcc6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13.015H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9a2.18 2.18 0 0 0-2.18 2.18v.05h0v7.29h39v-3.42a1.83 1.83 0 0 0-1.79-1.87Z");
}

</style>
