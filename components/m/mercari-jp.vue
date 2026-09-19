<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjvxkrczm"/><circle class="gl05c_apj"/><path class="klz_v6x3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mercari-jp" /></template>
<style>
.fjvxkrczm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.17 7.743l-8.209-4.497a2 2 0 0 0-1.922 0l-16.887 9.25a2 2 0 0 0-1.039 1.754v19.5a2 2 0 0 0 1.04 1.754l16.886 9.25a2 2 0 0 0 1.922 0l16.887-9.25a2 2 0 0 0 1.04-1.754V20.828");
}

.gl05c_apj {
  cx: 37.115px;
  cy: 14.963px;
  r: 8.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.klz_v6x3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.556 33.028v-4.727c0-1.583-1.11-3.474-2.481-4.225S9.594 24 9.594 25.582v4.728m4.962-2.009c0-1.582 1.11-2.257 2.481-1.506s2.481 2.642 2.481 4.224v4.728");
}

</style>
