<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9mc22bti"/><circle class="l7arfhb-e"/><path class="rd3w869rw"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:movirt" /></template>
<style>
.c9mc22bti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.763 20.078v8.057c0 .806.535 1.343 1.337 1.343h.4m-3.207-7.251h2.94m-7.937 2.685a2.687 2.687 0 0 1 2.673-2.685h0m-2.673 0v7.251");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.l7arfhb-e {
  cx: 26.735px;
  cy: 19.004px;
  r: 0.75px;
  fill: currentColor;
}

.rd3w869rw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.735 22.227v7.251m-2.638-10.743l-3.475 10.743l-3.475-10.743m-4.973 10.743A2.687 2.687 0 0 1 9.5 26.792v-1.745a2.687 2.687 0 0 1 2.673-2.686h0a2.687 2.687 0 0 1 2.673 2.686v1.745a2.687 2.687 0 0 1-2.673 2.686");
}

</style>
