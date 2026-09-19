<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="wora0_rjx"/><path class="nc4ev2bxa"/><path class="qry88absa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sns-24" /></template>
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

.nc4ev2bxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.986 31.632c2.777 3.053 6.59 4.606 11.972 4.606c4.954 0 11.624-2.774 16.324-5.087M15.257 4.353c-1.979 3.997-4.38 10.768-3.953 16.609");
}

.qry88absa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.499 19.472c3.166 4.953 2.938 11.01 2.075 15.304M12.027 13.362a30 30 0 0 1 6.41-1.325");
}

.wora0_rjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.025 44.658a15 15 0 0 1-2.768-8.882c0-4.795 3.995-16.36 20.145-16.36a12.6 12.6 0 0 1 10.096 4.856M2.741 27.227a3.72 3.72 0 0 0 3.222 2.156c2.733 0 2.954-2.796 4.794-7.191c5.39-12.878 16.36-14.678 22.794-14.678a18 18 0 0 1 5.177.823");
}

</style>
