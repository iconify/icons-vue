<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="xv5a-4jsy"/><path class="wuukqgbbf"/><path class="bc41j6jse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:volleyball" /></template>
<style>
.bc41j6jse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.406 21.949c-5.972-2.128-13.88-1.117-21.18 2.284m-6.843-6.728c9.808-4.087 19.23-5.514 25.788-3.231M13.339 10.44c8.282-3.7 15.824-5.399 22.585-4.337");
}

.wuukqgbbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.828 43.433c5.027-3.925 8.396-11.249 9.417-19.234");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

.xv5a-4jsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.252 21.505c-1.478 10.562-5.063 19.433-10.389 23.92m18.694-24.327c-.952 9.1-3.266 16.54-7.582 21.9m-12.268-9.526C13.228 26.815 7.324 19.166 6.21 12.248M17.618 40.47C10.006 34.567 4.752 28.35 2.671 21.445M24.245 24.2c-6.587-4.976-11.297-11.745-11.991-18.204");
}

</style>
