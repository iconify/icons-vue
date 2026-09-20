<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bp5vbbpdd"/><path class="kmeit4bwu"/><circle class="wmtpevbdu"/><path class="brjf__bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tng-ewallet" /></template>
<style>
.bp5vbbpdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.451 27.798v8.009a3.946 3.946 0 0 1-3.945 3.947H8.446A3.946 3.946 0 0 1 4.5 35.808V12.193a3.946 3.946 0 0 1 3.945-3.947h30.06a3.946 3.946 0 0 1 3.946 3.946v8.215");
}

.brjf__bck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.246 19.474h5.997m-2.999 9.052v-9.052m9.201 9.052v-3.734a2.263 2.263 0 0 0-4.526 0m-.001 3.734v-5.997m13.236-.057a2.999 2.999 0 0 0-5.997 0v3.056a2.999 2.999 0 0 0 5.997 0h-2.998");
}

.kmeit4bwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.15 27.798a3.693 3.693 0 0 1-3.692-3.693v-.002a3.694 3.694 0 0 1 3.692-3.696h6.35a1 1 0 0 1 1 1v5.391a1 1 0 0 1-1 1z");
}

.wmtpevbdu {
  cx: 36.492px;
  cy: 24.146px;
  r: 1.717px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
