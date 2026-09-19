<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtw68sbgq"/><path class="zk6xgsbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:seecitv" /></template>
<style>
.vtw68sbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 40.7c-3.7 3-8.4 4.8-13.5 4.8c-11.9 0-21.5-9.6-21.5-21.5S12.1 2.5 24 2.5c5.1 0 9.8 1.8 13.5 4.8");
}

.zk6xgsbse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.6 27.7c-3 12.1-19.3 15.4-26.7 5.2c-7.6-10 .3-24.7 12.8-24");
}

</style>
