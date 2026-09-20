<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="r_p6o0blj"/><path class="ojs6n_bvj"/><circle class="ezlzp6bei"/><path class="s8acfgjrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unipolsai" /></template>
<style>
.ezlzp6bei {
  cx: 42.926px;
  cy: 19.965px;
  r: 0.75px;
  fill: currentColor;
}

.ojs6n_bvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.996 21.993v4.344");
}

.r_p6o0blj {
  cx: 17.996px;
  cy: 19.985px;
  r: 0.75px;
  fill: currentColor;
}

.s8acfgjrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.926 21.973v4.343m-10.216-.677c.402.523.906.718 1.607.718h.97c.904 0 1.636-.732 1.636-1.635v-.007c0-.904-.732-1.636-1.635-1.636h-1.07a1.637 1.637 0 0 1-1.638-1.637a1.64 1.64 0 0 1 1.64-1.641h.966c.701 0 1.205.195 1.607.718m-6.927-.718v5.737c0 .452.366.82.819.82h.246m10.508-1.64a1.639 1.639 0 1 1-3.278 0v-1.065a1.639 1.639 0 1 1 3.278 0m0 2.704v-4.343M15.64 26.357v-2.704a1.639 1.639 0 1 0-3.278 0m-.001 2.704v-4.343m-6.537-2.213v4.385a2.172 2.172 0 1 0 4.344 0V19.8m9.776 4.957a1.639 1.639 0 1 0 3.278 0v-1.065a1.639 1.639 0 1 0-3.278 0m0-1.64v6.557m4.961-4.917a1.639 1.639 0 1 1 3.278 0v1.065a1.639 1.639 0 1 1-3.278 0zm-6.879 4.475H6.252L4.5 27.034");
}

</style>
