<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="m9a2a1xgn"/><path class="rp6d0mb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:runna" /></template>
<style>
.m9a2a1xgn {
  cx: 32.572px;
  cy: 9.102px;
  r: 4.602px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rp6d0mb0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.943 33.458c3.357-1.88 5.63-5.466 5.63-9.587c0-6.066-4.919-10.984-10.985-10.984H10.826l5.047 6.308h4.078a4.676 4.676 0 0 1 2.61 8.555l-2.977-3.879h-8.758L25.893 43.5h8.757z");
}

</style>
