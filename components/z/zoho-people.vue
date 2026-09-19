<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="js29v8b6b"/><path class="h_31e9bid"/><path class="wt2a5phnj"/><path class="eoaij0h8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoho-people" /></template>
<style>
.eoaij0h8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.585 10.732c.595.344.963.979.963 1.667l.006 9.954c0 .688-.367 1.324-.963 1.669l-8.618 4.983a1.93 1.93 0 0 1-1.926 0l-8.624-4.974a1.93 1.93 0 0 1-.964-1.666l-.005-9.955c0-.688.367-1.324.963-1.669l8.619-4.982a1.93 1.93 0 0 1 1.926 0z");
}

.h_31e9bid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.78 23.97a1.93 1.93 0 0 0-.963 1.667l-.006 9.954c0 .688.368 1.324.964 1.669l8.617 4.983c.596.344 1.33.344 1.926 0l8.625-4.974c.595-.344.962-.979.963-1.666l.005-9.955c0-.688-.367-1.324-.963-1.669l-8.619-4.983a1.93 1.93 0 0 0-1.926 0z");
}

.js29v8b6b {
  cx: 24.004px;
  cy: 14.888px;
  r: 2.408px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wt2a5phnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.22 23.97c.595.344.963.979.963 1.667l.006 9.954c0 .688-.367 1.324-.963 1.669l-8.618 4.983a1.93 1.93 0 0 1-1.926 0l-8.624-4.974a1.93 1.93 0 0 1-.964-1.666l-.005-9.955c0-.688.367-1.324.963-1.669l8.619-4.983a1.93 1.93 0 0 1 1.926 0z");
}

</style>
