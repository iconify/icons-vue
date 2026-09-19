<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="a8oj_8b7n"/><path class="sz5pz0bic"/><rect class="pq8jjwbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ovpay" /></template>
<style>
.a8oj_8b7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.013 29.594v3.393A2.513 2.513 0 0 1 31.5 35.5h0a2.5 2.5 0 0 1-1.777-.736");
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

.pq8jjwbrl {
  width: 6.66px;
  height: 10.052px;
  x: 16.349px;
  y: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.33px;
  ry: 3.33px;
}

.sz5pz0bic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.013 25.448v4.146a2.513 2.513 0 0 1-2.513 2.513h0a2.513 2.513 0 0 1-2.513-2.513v-4.146m-2.554 4.146a2.513 2.513 0 0 1-2.513 2.513h0a2.513 2.513 0 0 1-2.513-2.513v-1.633a2.513 2.513 0 0 1 2.513-2.513h0a2.513 2.513 0 0 1 2.513 2.513m0 4.146v-6.659m-12.446 4.146a2.513 2.513 0 0 0 2.513 2.513h0a2.513 2.513 0 0 0 2.513-2.513v-1.633a2.513 2.513 0 0 0-2.513-2.513h0a2.513 2.513 0 0 0-2.513 2.513m0-2.513V35.5m17.664-23l-3.33 10.052l-3.33-10.052");
}

</style>
