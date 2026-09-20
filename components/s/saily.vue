<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="joi_o679o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saily" /></template>
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

.joi_o679o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.017 26.955c.981 1.277 2.211 1.753 3.923 1.753h2.369a3.99 3.99 0 0 0 3.991-3.991V24.7a3.99 3.99 0 0 0-3.991-3.992h-2.613a3.996 3.996 0 0 1-3.996-3.996a4.004 4.004 0 0 1 4.004-4.004h2.356c1.712 0 2.942.476 3.923 1.753m1.31 19.453c-2.888-1.667-3.445 1.378-6.168 1.378s-3.28-3.045-6.169-1.378");
}

</style>
