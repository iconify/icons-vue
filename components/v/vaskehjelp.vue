<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qoo6l5ygy"/><circle class="xr3iwxbxr"/><circle class="bv3tfxnvv"/><circle class="s82swlb8i"/><path class="mdmcg5bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vaskehjelp" /></template>
<style>
.bv3tfxnvv {
  cx: 20.394px;
  cy: 13.205px;
  r: 4.246px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mdmcg5bzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.982 20.202a3.414 3.414 0 1 0-6.827 0");
}

.qoo6l5ygy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.306 20.202h25.388m-23.254 0l1.037 21.12a2.29 2.29 0 0 0 2.287 2.178h14.472a2.29 2.29 0 0 0 2.287-2.177l1.038-21.12m-10.91 3.328l10.245 10.192");
}

.s82swlb8i {
  cx: 27.392px;
  cy: 6.164px;
  r: 1.664px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xr3iwxbxr {
  cx: 21.845px;
  cy: 30.144px;
  r: 1.92px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
