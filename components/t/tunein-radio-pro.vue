<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="brbipbq1a"/><rect class="cs8eltbnl"/><path class="vqb0nwf6q"/><rect class="sllw01bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tunein-radio-pro" /></template>
<style>
.brbipbq1a {
  width: 24px;
  height: 14px;
  x: 4.5px;
  y: 19px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.cs8eltbnl {
  width: 15px;
  height: 14px;
  x: 28.5px;
  y: 15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.sllw01bwt {
  width: 2.99px;
  height: 4.513px;
  x: 40.51px;
  y: 31.132px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.495px;
  ry: 1.495px;
}

.vqb0nwf6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.429 29.071H26.5m-3.071-6.142H26.5M23.429 26h2.002m-2.002-3.071v6.142M6.5 22.929h4.069m-2.035 6.142v-6.142m9.252 6.142v-6.142l4.069 6.142v-6.142m-9.712.001v4.106a2.034 2.034 0 0 0 4.069 0V22.93m16.865-4.001v6.142m1.777 0v-6.142l4.069 6.142v-6.142m-8.438 16.716v-4.513h1.477a1.515 1.515 0 0 1 0 3.032h-1.477m4.909 1.481v-4.513h1.477a1.515 1.515 0 0 1 0 3.032h-1.477m1.477 0l1.478 1.48");
}

</style>
