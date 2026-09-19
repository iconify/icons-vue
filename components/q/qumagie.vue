<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="k7zg2ub5g"/><path class="kvdpw7_wp"/><path class="lswe61bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qumagie" /></template>
<style>
.k7zg2ub5g {
  cx: 12.102px;
  cy: 12.042px;
  r: 4.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kvdpw7_wp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.246 36.493l-7.283-14.025l-3.883 6.938l-4.663 8.35a4.86 4.86 0 0 1-4.239 2.494h-4.801c-3.803 0-6.146-4.17-4.147-7.41l8.213-13.405c1.757-2.975 5.755-3.308 8.018-1.033");
}

.lswe61bzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.084 29.41l4.05 7.1a7.4 7.4 0 0 0 6.43 3.735h2.606c4.094 0 6.655-4.43 4.612-7.978L32.58 16.285c-1.958-3.4-6.855-3.427-8.85-.047l-10.095 17.11");
}

</style>
