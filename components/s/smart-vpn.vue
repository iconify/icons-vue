<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="eug0vra6a"/><path class="vo_andbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-vpn" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eug0vra6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.258 29.472h12.003v8.909H10.258zm2.038-3.474a4.031 4.031 0 0 1 8.059 0m0 .046v3.422m-8.06-3.41v3.375m-9.022-.094c2.948-2.2 4.74-1.892 6.985.135m10.097-.006c6.992-7.863 14.506-12.901 23.593-12.739");
}

.vo_andbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.347 27.75c4.378-8.676 12.49-15.408 22.06-14.68M3.851 31.387c2.948-2.2 4.161-1.874 6.406.153");
}

</style>
