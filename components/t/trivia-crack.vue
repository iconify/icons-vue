<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="rhb56hbui"/><path class="n7nhgs54t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trivia-crack" /></template>
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

.n7nhgs54t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.448 22.079c1.312-1.693 2.603-1.23 3.208-.77m-9.669-3.676c.63-1.004 1.709-.66 1.709-.66m7.386 1.912c-.63-1.004-1.517-.94-1.517-.94m4.363 4.464a8 8 0 0 1-13.856 0m1.192-1.139c-1.626-.49-2.18.302-2.327.803m14.481-.659c.677-.31 1.385.034 1.792.61");
}

.rhb56hbui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 10l-2.705 3.36A11 11 0 0 0 13 24c0 6.075 4.925 11 11 11s11-4.925 11-11a11 11 0 0 0-8.31-10.664zm4.772 4.09l4.137-8.59m-17.818 0l4.147 8.611m-5.929 7.449L5.5 19.778m37 0l-7.777 1.775m-2.145 9.288l9.909 7.902m-36.973 0l9.908-7.902M24 35v7.5m-3.782-23.163v2.929");
}

</style>
