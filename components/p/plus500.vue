<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="kl27w0bfd"/><rect class="s4679bpba"/><path class="rword1bfp"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plus500" /></template>
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

.kl27w0bfd {
  width: 6.107px;
  height: 9.219px;
  x: 20.716px;
  y: 23.357px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.152px;
  ry: 1.152px;
}

.rword1bfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 32.576h4.494c.637 0 1.153-.516 1.153-1.153V28.56c0-.636-.516-1.152-1.153-1.152H12.5v-4.05h5.647m5.623-2.172v-5.762m-2.881 2.881h5.761");
}

.s4679bpba {
  width: 6.107px;
  height: 9.219px;
  x: 29.392px;
  y: 23.357px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.152px;
  ry: 1.152px;
}

</style>
