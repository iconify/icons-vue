<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xeh91d5ig"/><path class="fqslv3b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:patient-access" /></template>
<style>
.fqslv3b6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.894 15.85L24 10.746c4.232-4.232 11.094-4.232 15.326 0s4.232 11.094 0 15.326l-13.67 13.67a2.34 2.34 0 0 1-3.313 0L8.674 26.07c-4.232-4.232-4.232-11.094 0-15.326s11.094-4.232 15.326 0a10.837 10.837 0 0 1-2.866 17.381c-.93.336-1.349 1.394-.54 2.202l7.238 7.238M13.785 20.96l-5.111 5.112");
}

.xeh91d5ig {
  cx: 16.339px;
  cy: 18.406px;
  r: 3.612px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
