<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rkg2c8b1s"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:playtv" /></template>
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

.rkg2c8b1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.394 11.501v10.277H37.5m-26.16 0V11.5h9.7c1.901 0 3.443 1.545 3.443 3.451s-1.542 3.452-3.444 3.452h-9.698M37.5 26.222l-6.41 5.139l-6.409-5.139m6.409 10.277v-5.138m-6.797 1.734H11.628M10.5 36.499l3.404-10.277h8.112l3.404 10.277");
}

</style>
