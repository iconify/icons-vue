<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q12ikb-1i"/><circle class="p3dvgbckz"/><circle class="zs5fngv2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:music-editor" /></template>
<style>
.p3dvgbckz {
  cx: 19.181px;
  cy: 39.41px;
  r: 2.466px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q12ikb-1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 13.97v3.362m6.5-7.285v11.207m3.25-15.129v19.052m3.25-15.13v11.207m3.25-9.526v7.845M24 8.366v14.57M7.75 11.728v7.845m19.5-7.845v7.845m3.25-9.526v11.207m3.25-15.129v19.052M37 10.047v11.207m3.25-9.526v7.845m3.25-5.603v3.362m-25.103 8.965l8.405 11.207m-5.604 0l8.405-11.207");
}

.zs5fngv2v {
  cx: 28.819px;
  cy: 39.41px;
  r: 2.466px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
