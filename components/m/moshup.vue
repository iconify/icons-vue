<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hyxedwbpu"/><path class="gx_dm4b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moshup" /></template>
<style>
.gx_dm4b2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h8.597L24 21.062L33.904 5.5H42.5v37H31.4V30.109L24 41.738l-7.4-11.629V42.5H5.5z");
}

.hyxedwbpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.05 36.95v-25.9L24 31.4l12.95-20.35v25.9");
}

</style>
