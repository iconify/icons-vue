<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="aex80ackq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sky-go" /></template>
<style>
.aex80ackq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24h37M21.798 8.73v8.972m.001-1.906l4.061-4.042m-2.768 2.756l3.192 3.178M15.926 17.2c.41.344.852.501 1.845.501h.503c.819 0 1.483-.665 1.483-1.486s-.664-1.486-1.483-1.486h-1.006c-.82 0-1.483-.665-1.483-1.486s.664-1.486 1.483-1.486h.503c.993 0 1.435.158 1.844.502m10.503 5.443l-2.389-5.944m4.486 0L29.05 20.73m-.429 12.52l-9.242 5.336V27.914z");
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
