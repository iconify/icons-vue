<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="up9-fac5k"/><path class="cwtd37blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:network-speed" /></template>
<style>
.cwtd37blr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 20.585a23.808 23.808 0 0 0-39 0m39 0l-21.483 8.463a5.558 5.558 0 1 0 6.212 8.779l.015.02Z");
}

.up9-fac5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.628 24.08a14.704 14.704 0 0 0-22.673 1.725");
}

</style>
