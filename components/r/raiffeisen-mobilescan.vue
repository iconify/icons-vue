<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eglwu-kdz"/><circle class="vi_nxfq0r"/><path class="zjjagt8rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:raiffeisen-mobilescan" /></template>
<style>
.eglwu-kdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.31 5.5H9.5a4 4 0 0 0-4 4v9.81m37 0V9.5a4 4 0 0 0-4-4h-9.81M5.5 28.69v9.81a4 4 0 0 0 4 4h9.81m23.19-9.743V28.69M28.691 42.5h4.065");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zjjagt8rt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 42.5v-8h2.619c1.48 0 2.681 1.203 2.681 2.687s-1.2 2.686-2.681 2.686H35.85m2.619 0l2.619 2.625");
}

</style>
