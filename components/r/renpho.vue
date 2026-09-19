<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ax8ft9b1p"/><ellipse class="wsrzoebaa"/><path class="nsne0bs2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:renpho" /></template>
<style>
.ax8ft9b1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.835 42.5l18.169-17.688a12.45 12.45 0 0 0 9.938-3.36a10.59 10.59 0 0 0 3.187-9.417");
}

.nsne0bs2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.165 42.493L31.791 32.394c-7.795 3.081-15.218-.348-15.218-.348");
}

.wsrzoebaa {
  cx: 23.739px;
  cy: 11.52px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.184px;
  ry: 6.02px;
}

</style>
