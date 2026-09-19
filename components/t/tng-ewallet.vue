<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bp5vbbpdd"/><path class="lmjsygiun"/><circle class="wmtpevbdu"/><path class="y60j_1_ky"/>`;
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

.lmjsygiun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.15 27.798a3.693 3.693 0 0 1-3.692-3.693v-.002h0a3.694 3.694 0 0 1 3.692-3.696h6.35a1 1 0 0 1 1 1v5.391a1 1 0 0 1-1 1z");
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

.y60j_1_ky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.246 19.474h5.997m-2.999 9.052v-9.052m9.201 9.052v-3.734a2.263 2.263 0 0 0-2.263-2.263h0a2.263 2.263 0 0 0-2.264 2.263m0 3.734v-5.997m13.236-.057a3 3 0 0 0-2.998-2.998h0a3 3 0 0 0-2.999 2.998v3.056a3 3 0 0 0 2.999 2.998h0a3 3 0 0 0 2.998-2.998h-2.998");
}

</style>
