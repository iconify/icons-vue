<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rmdhj9boo"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:renfe" /></template>
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

.rmdhj9boo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.487 26.031a2.34 2.34 0 0 1-2.034 1.181h0a2.34 2.34 0 0 1-2.34-2.34V23.35a2.34 2.34 0 0 1 2.34-2.34h0a2.34 2.34 0 0 1 2.34 2.34v.76h-4.68m-4.198 3.103V19.49a1.64 1.64 0 0 1 1.639-1.639h0c.806 0 1.31.239 1.655.686m-4.682 2.473h3.277m-5.58 6.203v-3.862a2.34 2.34 0 0 0-2.341-2.34h0a2.34 2.34 0 0 0-2.341 2.34m0 3.862V21.01m-2.987 5.021a2.34 2.34 0 0 1-2.034 1.181h0a2.34 2.34 0 0 1-2.34-2.34V23.35a2.34 2.34 0 0 1 2.34-2.34h0a2.34 2.34 0 0 1 2.34 2.34v.76h-4.68m-4.42-.76a2.34 2.34 0 0 1 2.341-2.34h0m-2.341-.001v6.204");
}

</style>
