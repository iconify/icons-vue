<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xm0_7wbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ufc" /></template>
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

.xm0_7wbmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.843 29.627h-3.438c-1.428 0-2.21-1.158-1.746-2.586l1.977-6.082c.464-1.428 1.997-2.586 3.425-2.586h3.44m-13.437 0h5.627m-9.284 11.254L22.236 24h3.657m-5.027-5.627l-2.769 8.52c-.49 1.51-2.112 2.734-3.621 2.734h-1.99c-1.509 0-2.335-1.224-1.845-2.733l2.769-8.521");
}

</style>
