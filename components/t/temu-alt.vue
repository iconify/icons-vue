<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="g-zw--xyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:temu-alt" /></template>
<style>
.g-zw--xyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.895 28.031V19.96l4.039 8.08l4.04-8.068v8.068M9.5 19.96h5.353m-2.676 8.08v-8.08m20.97 0v5.404a2.676 2.676 0 1 0 5.353 0V19.96M16.813 24h2.634m1.406 4.04h-4.04v-8.08h4.04");
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
