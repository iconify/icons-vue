<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rf9jkpbjh"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:neo-mobile" /></template>
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

.rf9jkpbjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13 29.114V18.886l6.776 10.228V18.886m7.277 8.938a2.557 2.557 0 0 1-4.779-1.267v-1.662a2.557 2.557 0 1 1 5.114 0v.831h-5.114m7.612-.831a2.557 2.557 0 1 1 5.114 0v1.662a2.557 2.557 0 1 1-5.114 0z");
}

</style>
