<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="hbg-bizli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:motiontracker" /></template>
<style>
.hbg-bizli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.75 32.503h4.526c.838 0 1.517.841 1.517 1.879v2.32c0 1.038-.68 1.879-1.517 1.879H31.75c-.838 0-1.518-.841-1.518-1.879v-2.32c0-1.038.68-1.879 1.518-1.879M5.591 34.916l36.856-21.528M24.152 5.743l18.295 25.103m-4.451 4.561l1.72-2.4l-.001.3l-.02 4.502z");
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
