<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzgjxybrw"/><path class="y6wb3fbvd"/><path class="blou_rbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifi-pro-ftp-server" /></template>
<style>
.blou_rbow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.534 30.484a3.94 3.94 0 0 0-5.032-.014v.014m2.506 1.612a1.58 1.58 0 1 0 1.58 1.58h0a1.58 1.58 0 0 0-1.58-1.58m4.928-4.343a7.744 7.744 0 0 0-9.856 0m12.224-2.866a11.45 11.45 0 0 0-14.608 0");
}

.y6wb3fbvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.295h-39v18.72a2.18 2.18 0 0 0 2.16 2.2h34.66a2.18 2.18 0 0 0 2.18-2.18v-.02Z");
}

.zzgjxybrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13.015H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9a2.18 2.18 0 0 0-2.18 2.18v7.34h39v-3.42a1.83 1.83 0 0 0-1.79-1.87Z");
}

</style>
