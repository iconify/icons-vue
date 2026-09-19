<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="je4nxhb_b"/><circle class="au4zyrb7u"/><path class="g7ogrwbtq"/><path class="t06eq9lhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wmu" /></template>
<style>
.au4zyrb7u {
  cx: 15.873px;
  cy: 20.348px;
  r: 4.374px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g7ogrwbtq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.974 9.574h7.797l1.148 3.616H10.827zm15.272 14.524H43.5v14.328H20.82V27.505m0 0H6.2c-.942 0-1.7-.759-1.7-1.7V14.89c0-.942.758-1.7 1.7-1.7h19.345c.942 0 1.7.758 1.7 1.7v9.206");
}

.je4nxhb_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.245 24.097v1.707c0 .942-.758 1.7-1.7 1.7h-4.726");
}

.t06eq9lhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.423 28.653v6.102l7.474-3.051z");
}

</style>
