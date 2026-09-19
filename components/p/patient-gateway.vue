<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g63gv0b2r"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:patient-gateway" /></template>
<style>
.g63gv0b2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.854 36.5c2.912-1.185 5.982-.884 9.18-.895c3.495-.012 7.216.312 9.183-1.7m-18.363-1.337c2.912-1.185 5.982-.884 9.18-.895c3.495-.011 7.216.312 9.183-1.697m-.869-9.198v6.847m-5.541-6.847v7.994m-5.542-7.994v7.994m-5.538-7.994v7.994m17.419-14.194l-9.18-3.078l-9.183 3.078m.064 3.348h18.36");
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
