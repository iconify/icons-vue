<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="qzcjynb7s"/><path class="g3dl0xb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:screen-recorder" /></template>
<style>
.g3dl0xb-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.8 27.71l8.32 7.37A1.43 1.43 0 0 0 43.5 34V14a1.43 1.43 0 0 0-2.38-1.07l-8.32 7.36");
}

.qzcjynb7s {
  width: 28.3px;
  height: 25.12px;
  x: 4.5px;
  y: 11.44px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.49px;
}

</style>
