<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ypi47wb8h"/><path class="kv_39pk3y"/><path class="u9vx4ebcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoftpowerpoint" /></template>
<style>
.kv_39pk3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16v16a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V16a2 2 0 0 0-2-2h-16a2 2 0 0 0-2 2");
}

.u9vx4ebcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.43 34a18.5 18.5 0 1 0 0-20");
}

.ypi47wb8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.66 29V18h3.7a3.7 3.7 0 0 1 0 7.39h-3.7");
}

</style>
