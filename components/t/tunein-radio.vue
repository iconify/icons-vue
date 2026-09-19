<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="gqm9j2brv"/><rect class="p9p31sbte"/><path class="uoibhab5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tunein-radio" /></template>
<style>
.gqm9j2brv {
  width: 24px;
  height: 14px;
  x: 4.5px;
  y: 19px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

.p9p31sbte {
  width: 15px;
  height: 14px;
  x: 28.5px;
  y: 15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

.uoibhab5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.429 29.071H26.5m-3.071-6.142H26.5M23.429 26h2.002m-2.002-3.071v6.142M6.5 22.929h4.069m-2.035 6.142v-6.142m9.252 6.142v-6.142l4.069 6.142v-6.142m-9.712.001v4.106a2.034 2.034 0 0 0 4.069 0V22.93m16.865-4.001v6.142m1.777 0v-6.142l4.069 6.142v-6.142");
}

</style>
