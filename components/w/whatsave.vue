<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yl_1kybwh"/><circle class="yosn965cz"/><path class="zf_7xfb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whatsave" /></template>
<style>
.yl_1kybwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.44 25.875a21.5 21.5 0 0 1-25.152 19.298M4.578 14.915a21.5 21.5 0 0 1 40.903 7.213M16.67 44.203C6.193 40.39.37 29.203 3.255 18.436");
}

.yosn965cz {
  cx: 24.022px;
  cy: 24px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zf_7xfb-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.022 29.604V18.397m-3.569 7.759l3.57 3.448l3.568-3.448");
}

</style>
