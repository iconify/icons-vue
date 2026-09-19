<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xt-z2zpze"/><path class="w36qbtl9f"/><path class="vvby5d_3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:material-calculator" /></template>
<style>
.vvby5d_3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 27.169V9.5a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h17.67M24 24v3.17M27.168 24H24m15.33 0h3.17");
}

.w36qbtl9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24H5.5m0 0H24V5.5m12.33 6.59l-6.16 6.15m0-6.15l6.16 6.15M14.37 37.6v-8.7m4.35 4.35h-8.71m27.59-1.14h-8.7m8.7 2.81h-8.7M18.7 15.15H10");
}

.xt-z2zpze {
  cx: 33.25px;
  cy: 33.25px;
  r: 11.07px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
