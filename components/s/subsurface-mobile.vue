<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cn0rv_rjz"/><circle class="eomsm-l2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:subsurface-mobile" /></template>
<style>
.cn0rv_rjz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.544 11.75C8.272 9.222 17.937 9.907 24.002 11c6.064 1.094 13.579 1.017 18.328-.804m-18.515 9.305c-.244 3.57-1.191 4.085-1.856 5.825c1.431 1.074 2.826 2.1 4.532 3.533c.348 1.981.99 3.805 1.764 5.557c1.88-.932 4.074-1.519 6.492-1.861m-12.788-7.228c.1 1.922.081 3.453.005 4.792c-1.621 1.523-2.306 2.695-3.725 4.487c.203 1.351.512 1.897.576 4.328m-.192-14.547l1.816-6.487");
}

.eomsm-l2q {
  cx: 25.036px;
  cy: 15.584px;
  r: 2.289px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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
