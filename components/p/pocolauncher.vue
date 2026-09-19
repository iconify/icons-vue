<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="frohctb9d"/><path class="h-hesfbdl"/><path class="jb3pxr2rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocolauncher" /></template>
<style>
.frohctb9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.49 20a15.51 15.51 0 1 1 10.33 14.63M24 14.83A5.18 5.18 0 1 0 29.18 20A5.19 5.19 0 0 0 24 14.83");
}

.h-hesfbdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.83a10.34 10.34 0 0 1 .53 20.67a15.5 15.5 0 0 0-.53-31");
}

.jb3pxr2rn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5A15.53 15.53 0 0 0 8.49 20v18.33a5.17 5.17 0 1 0 10.33 0V20A12.65 12.65 0 0 1 31.45 7.38a12 12 0 0 1 1.7.12a15.45 15.45 0 0 0-9.15-3");
}

</style>
