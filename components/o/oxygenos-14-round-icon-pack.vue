<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f0cq-3bre"/><rect class="j3s9ivbxi"/><path class="cnd4pq4bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oxygenos-14-round-icon-pack" /></template>
<style>
.cnd4pq4bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.404 42.304a18 18 0 0 1 24.9-24.9");
}

.f0cq-3bre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.18 39.348V22.9l-9.674 12.108h10.798M20.942 27.23c1.934 0 4.506-3.299 4.506-4.331v16.523");
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

</style>
