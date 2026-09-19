<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1axbnbhf"/><path class="lx18-rbnc"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:playo" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.lx18-rbnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.981 20.16c.516 2.545-1.062 4.389-2.414 5.055m5.354 2.659c-.516-2.546 1.062-4.39 2.415-5.056");
}

.m1axbnbhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.752 19.893v8.213h2.264m-9.627 0v-8.213h2.67c1.54 0 2.771 1.232 2.771 2.772s-1.232 2.772-2.772 2.772h-2.67m11.377 2.669l2.772-8.213l2.772 8.213m5.056-8.213L27.696 24l-2.67-4.107m2.67 8.213V24m11.915 0a4.175 4.175 0 0 1-4.175 4.175h0A4.175 4.175 0 0 1 31.26 24h0a4.175 4.175 0 0 1 4.175-4.175h0A4.175 4.175 0 0 1 39.61 24");
}

</style>
