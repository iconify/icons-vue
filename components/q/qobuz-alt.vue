<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nef_-ncdj"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qobuz-alt" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.nef_-ncdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.633 21.438H38.5l-3.867 5.124H38.5m-10.15-5.124v3.19c0 1.068.866 1.934 1.933 1.934h0a1.933 1.933 0 0 0 1.934-1.934v-3.19m0 3.19v1.934m-10.15-3.19c0-1.068.865-1.934 1.933-1.934h0c1.068 0 1.933.866 1.933 1.934v1.256A1.933 1.933 0 0 1 24 26.562h0a1.933 1.933 0 0 1-1.933-1.934m0 1.934v-7.734m-6.284 4.544a1.933 1.933 0 1 1 3.867 0v1.256a1.933 1.933 0 1 1-3.867 0zm-2.416 1.256a1.933 1.933 0 0 1-1.934 1.934h0A1.933 1.933 0 0 1 9.5 24.628v-1.256c0-1.068.866-1.934 1.933-1.934h0c1.068 0 1.934.866 1.934 1.934m0-1.934v7.734");
}

</style>
