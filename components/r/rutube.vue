<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkz5-vbjv"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rutube" /></template>
<style>
.gkz5-vbjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 14.203h16.86a3.624 3.624 0 0 1 3.622 3.623v4.658c0 2-1.623 3.623-3.623 3.623H13.5zm16.046 11.904l4.954 7.69m-21-7.69v7.69");
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
