<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="aw464lb-q"/><path class="tbw8ynbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metrozone" /></template>
<style>
.aw464lb-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.623 19.311a4.688 4.688 0 1 1 9.377 0v7.736m-9.377-12.424v12.425");
}

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

.tbw8ynbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.311a4.688 4.688 0 1 1 9.377 0v7.736m-7.843 6.33V28.54l3.163 4.837V28.54m-14.074 0h3.163l-3.163 4.837h3.163m13.204-2.418h1.558m.829 2.418H30.99V28.54h2.387m-11.717 0c.874 0 1.582.717 1.582 1.602v1.633c0 .885-.708 1.602-1.582 1.602h0a1.59 1.59 0 0 1-1.581-1.602v-1.633c0-.885.708-1.602 1.582-1.602");
}

</style>
