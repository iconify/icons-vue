<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hels24b_z"/><path class="mrkqhkbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:step" /></template>
<style>
.hels24b_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 32.128l6.915-11.585L24 27.458l-6.915 11.585zm6.915-11.586L19.33 8.957l11.585 6.915L24 27.457z");
}

.mrkqhkbsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 27.457l6.915-11.585L42.5 22.787l-6.915 11.585z");
}

</style>
