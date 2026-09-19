<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzq_7zbob"/><rect class="j3s9ivbxi"/><path class="yjx7_tv4v"/><path class="g13564neq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:termux-float" /></template>
<style>
.g13564neq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.006 8.5h10.98c.836 0 1.514.892 1.514 1.992v10.025c0 1.1-.678 1.992-1.514 1.992h-10.98c-.837 0-1.515-.892-1.515-1.992V10.491c0-1.1.678-1.991 1.515-1.991");
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

.mzq_7zbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.5 25.327l10.127 5.853L10.5 37.032m22 0H21.673");
}

.yjx7_tv4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.73 10.448h4.153c.316 0 .573.293.573.656v3.987c0 .362-.257.656-.573.656h-4.154c-.316 0-.573-.294-.573-.656v-3.987c0-.362.257-.656.573-.656");
}

</style>
