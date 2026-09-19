<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zla0nyb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meteo" /></template>
<style>
.zla0nyb5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16a8 8 0 1 1-8 8a8 8 0 0 1 8-8m-.02 19.82v6.68m-8.35-10.16l-4.72 4.73m1.27-13.09H5.5m10.16-8.35l-4.73-4.72m13.09 1.27V5.5m8.35 10.16l4.72-4.73m-1.27 13.09h6.68m-10.16 8.35l4.73 4.72");
}

</style>
