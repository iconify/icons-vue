<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yvu47bcul"/><path class="b_900boks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:turo" /></template>
<style>
.b_900boks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.832 27.2v-6.4h2.095c1.185 0 2.145.962 2.145 2.15s-.96 2.149-2.145 2.149h-2.095m2.096 0l2.095 2.1M9.522 20.8h4.24m-2.12 6.4v-6.4m5.035 0v4.28a2.12 2.12 0 1 0 4.24 0V20.8m12.191 0zc1.17 0 2.12.95 2.12 2.12v2.16a2.12 2.12 0 0 1-4.24 0v-2.16c0-1.17.95-2.12 2.12-2.12");
}

.yvu47bcul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37 17.5l6.5 6.5l-6.5 6.5H4.5v-13z");
}

</style>
