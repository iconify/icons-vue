<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4j2pnbpt"/><circle class="b-a5pq1bc"/><path class="soz0jhb5g"/><path class="y5r96bb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opentimer" /></template>
<style>
.b-a5pq1bc {
  cx: 23.738px;
  cy: 24.206px;
  r: 0.75px;
  fill: currentColor;
}

.j4j2pnbpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.814 38.195a16.15 16.15 0 0 1-16.153 0m8.077-3.275v-1.714m-5.352.28L19.243 32m-4.775-2.432l1.485-.857m-2.919-4.494h1.714m-.28-5.352l1.485.857m2.433-4.775l.857 1.484m4.495-2.918v1.714m5.352-.28l-.857 1.484m4.774 2.434l-1.484.857m2.918 4.495h-1.714m.28 5.351l-1.484-.857m-2.433 4.775L28.233 32");
}

.soz0jhb5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.592 24.06l-5.356-5.356m-6.502 16.311a16.153 16.153 0 1 1 24.378-.426m-24.378.426C9.892 36.92 7.987 38.67 8.824 43.5h7.056a11.9 11.9 0 0 1-.22-5.305");
}

.y5r96bb-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.814 38.195c1.044 1.06 1.677 2.642 1.446 5.305h7.14c.202-3.85-1.548-6.603-4.288-8.911M32.704 10.75c1.97.976 2.92-2.5.866-3.536c-7.235-3.648-12.367-3.59-19.743 0c-2.144 1.043-.995 4.39.897 3.59");
}

</style>
