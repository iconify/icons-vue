<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="glujv24bj"/><rect class="k9vu-pbjy"/><rect class="ji5h0168f"/><path class="ioqd729me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toyou" /></template>
<style>
.glujv24bj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 12.883h6.091m-3.045 9.194v-9.194m3.045 13.04l-3.045 4.597l-3.046-4.597m3.046 9.194V30.52m13.863-4.597v6.149a3.046 3.046 0 1 0 6.09 0v-6.15");
}

.ioqd729me {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.409 22.077H35.5");
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

.ji5h0168f {
  width: 6.091px;
  height: 9.195px;
  x: 20.564px;
  y: 25.923px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.046px;
  ry: 3.046px;
}

.k9vu-pbjy {
  width: 6.091px;
  height: 9.195px;
  x: 20.564px;
  y: 12.883px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.046px;
  ry: 3.046px;
}

</style>
