<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7h9q8s0t"/><path class="hlbi7u7qf"/><circle class="np6s29gah"/><path class="k77pe-bvx"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mijnsimpel" /></template>
<style>
.d7h9q8s0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.29 23.585a1.95 1.95 0 0 1 3.902 0v3.22m-3.903-5.171v5.17");
}

.hlbi7u7qf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.19 23.585a1.95 1.95 0 0 1 3.902 0v3.22");
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

.k77pe-bvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.107 21.634v5.17m-5.484-.436c.356.3.74.436 1.604.436h.438a1.292 1.292 0 0 0 0-2.585H9.79c-.713 0-1.29-.578-1.29-1.292s.577-1.293 1.29-1.293h.437c.864 0 1.249.137 1.605.437M38.232 19v6.829c0 .539.437.975.975.975h.293m-3.603-.984a1.95 1.95 0 0 1-3.646-.966v-1.269a1.95 1.95 0 0 1 3.902 0v.634h-3.902m-5.981.635a1.95 1.95 0 0 0 3.902 0v-1.269a1.95 1.95 0 0 0-3.902 0m.001-1.951v7.804");
}

.np6s29gah {
  cx: 14.107px;
  cy: 19.245px;
  r: 0.75px;
  fill: currentColor;
}

</style>
