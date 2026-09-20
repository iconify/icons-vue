<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cgb9apb7y"/><circle class="rxglybcwx"/><path class="ip491g5ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rentcafe-resident" /></template>
<style>
.cgb9apb7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.105 2.5c-11.874 0-21.5 9.626-21.5 21.5s9.626 21.5 21.5 21.5c10.705-.013 19.77-7.9 21.264-18.5h-7.1a14.5 14.5 0 0 1-14.163 11.5c-8.009 0-14.5-6.492-14.5-14.5s6.491-14.5 14.5-14.5A14.5 14.5 0 0 1 38.289 21h7.106C43.9 10.39 34.821 2.5 24.106 2.5");
}

.ip491g5ix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.607 35.717c2.473-1.092 5.446-1.68 8.498-1.68c3.042 0 6.007.585 8.476 1.67");
}

.rxglybcwx {
  cx: 24.105px;
  cy: 24px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
