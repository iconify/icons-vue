<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mq-s1bccp"/><rect class="j3s9ivbxi"/><circle class="jfs1njbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:welink" /></template>
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

.jfs1njbha {
  cx: 28.769px;
  cy: 21.276px;
  r: 0.75px;
  fill: currentColor;
}

.mq-s1bccp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.035 20.806l1.656 6.772l.892-.022l.882-4.205h.914l1.064 4.183h.85l1.612-6.684m2.859 4.998l2.439-1.595m.131-.216a2.25 2.25 0 0 0-1.152-.853a2.215 2.215 0 0 0-2.542.93a2.3 2.3 0 0 0-.352 1.402c.036.49.234.966.555 1.333c.32.368.762.625 1.236.72a2.22 2.22 0 0 0 2.427-1.205q.047-.096.086-.197m1.932-4.983l.022 5.758l.197.479l.228.123l2.963.01m1.827-4.564l.015 4.68m2.403.124v-4.032l.274-.37l2.508-.031l.578.571v3.77m2.418-6.426v6.29m3.258-4.171l-2.537 1.704v.655l2.494 1.802");
}

</style>
