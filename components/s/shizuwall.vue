<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_qh0it6k"/><path class="y2gnocbmx"/><circle class="b0-jpm_jk"/><path class="ccnz1tdaj"/><circle class="av6t_dbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shizuwall" /></template>
<style>
.av6t_dbxn {
  cx: 28.854px;
  cy: 11.766px;
  r: 1.107px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.b0-jpm_jk {
  cx: 19.146px;
  cy: 11.766px;
  r: 1.107px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ccnz1tdaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.376 16.649h1.851c.568 15.554-.29 20.38-13.227 26.851c-12.938-6.472-13.795-11.297-13.227-26.851h1.85m16.456-9.534l1.79-2.615");
}

.y_qh0it6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.376 16.649C35.022 10.665 30.072 5.918 24 5.918s-11.022 4.747-11.376 10.73zM18.921 7.115L17.131 4.5m5.027 33.178l3.684-3.684m-3.684 0l3.684 3.684m-5.912-5.91a5.74 5.74 0 0 1 8.14-.001m-10.893-2.753a9.65 9.65 0 0 1 13.646 0");
}

.y2gnocbmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.516 26.321c-2.44-2.43-5.8-3.938-9.516-3.938s-7.076 1.508-9.516 3.938");
}

</style>
