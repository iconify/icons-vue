<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="qzb6lfbbf"/><rect class="l9o28-btl"/><rect class="zyw87vbpm"/><path class="am-dfy06e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nice-mind-map" /></template>
<style>
.am-dfy06e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11 19.25l10.545 9.5m4.91 0L37 19.25");
}

.l9o28-btl {
  width: 13px;
  height: 8px;
  x: 17.5px;
  y: 28.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.qzb6lfbbf {
  width: 13px;
  height: 8px;
  x: 4.5px;
  y: 11.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.zyw87vbpm {
  width: 13px;
  height: 8px;
  x: 30.5px;
  y: 11.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
