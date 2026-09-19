<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xqu808bai"/><path class="lnfjzlb8e"/><path class="xxw9m8b4p"/><path class="m9517sb2h"/><path class="npem9tbic"/><path class="aqbyr4yaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:snapbridge" /></template>
<style>
.aqbyr4yaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 20.468c0-4.419-8.283-8-18.5-8c-7.33 0-13.663 1.843-16.658 4.515");
}

.lnfjzlb8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.5c0 4.418 8.283 8 18.5 8s18.5-3.582 18.5-8");
}

.m9517sb2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.5v7c7.314 0 13.636 1.835 16.64 4.5m-7.39-10.429V6.693m0 20.735v6.908");
}

.npem9tbic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28.5v-7c-10.217 0-18.5-3.582-18.5-8s8.283-8 18.5-8s18.5 3.582 18.5 8");
}

.xqu808bai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 20.5c0 4.418-8.283 8-18.5 8s-18.5-3.582-18.5-8v-7");
}

.xxw9m8b4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.5v7c0 4.418 8.283 8 18.5 8s18.5-3.582 18.5-8v-21");
}

</style>
