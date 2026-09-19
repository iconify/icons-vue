<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o6958-7wm"/><path class="hid5yiibw"/><rect class="kt8qq7bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pdfn-up" /></template>
<style>
.hid5yiibw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.27 31.71v-7.59h2.485c1.405 0 2.543 1.14 2.543 2.549s-1.138 2.549-2.543 2.549H21.27m7.027 2.492v-7.59h1.708a3.32 3.32 0 0 1 3.32 3.32v.949a3.32 3.32 0 0 1-3.32 3.32zm6.974-3.795h2.467m-2.467 3.794V24.12h3.795");
}

.kt8qq7bnh {
  width: 25.083px;
  height: 14.55px;
  x: 17.114px;
  y: 20.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.897px;
  ry: 1.897px;
}

.o6958-7wm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.213 35.185v5.418a1.897 1.897 0 0 1-1.898 1.897H7.7a1.903 1.903 0 0 1-1.898-1.897V7.397c0-1.043.854-1.897 1.898-1.897h17.077v8.538c0 1.044.854 1.898 1.897 1.898h8.539v4.706M24.779 5.5l10.436 10.436");
}

</style>
