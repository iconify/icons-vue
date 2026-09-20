<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzf_3_rgu"/><ellipse class="qksh4hbpd"/><path class="x5ts-4bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ruthlesssettings" /></template>
<style>
.hzf_3_rgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.52 38.82a18.47 18.47 0 0 1-23.16-1.71m0 2.96a2.92 2.92 0 1 1-5.84 0m35.6-1.71a2.92 2.92 0 1 1-4.92 3.16m-24.84-1.43v-3m23.16 1.73l1.68 2.7");
}

.qksh4hbpd {
  cx: 24px;
  cy: 23.56px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12.05px;
  ry: 12.07px;
}

.x5ts-4bsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.12 38.36l-2.37-3.6a18.53 18.53 0 1 0-33.26-11.2v-.11v16.63");
}

</style>
