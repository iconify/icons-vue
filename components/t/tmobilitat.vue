<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g1__zk3ku"/><path class="jsbhhwgla"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tmobilitat" /></template>
<style>
.g1__zk3ku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.505 17.277h4.454m-4.454 13.446V17.277m9.55 7.899a3.36 3.36 0 0 1 3.361-3.36h0a3.36 3.36 0 0 1 3.361 3.36v5.547m-6.722-8.908v8.908");
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

.jsbhhwgla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.777 25.176a3.36 3.36 0 0 1 3.362-3.36h0a3.36 3.36 0 0 1 3.361 3.36v5.547m-16.539-4.454h-3.362M9.5 21.101v-3.824h3.823z");
}

</style>
