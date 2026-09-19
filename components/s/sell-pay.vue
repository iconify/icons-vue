<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xim15w3gg"/><rect class="v1ezxsa0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sell-pay" /></template>
<style>
.v1ezxsa0j {
  width: 8px;
  height: 8px;
  x: 10px;
  y: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.5px;
  ry: 2.5px;
}

.xim15w3gg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24.5v9c0 2.216 1.784 4 4 4h31c2.216 0 4-1.784 4-4v-19c0-2.216-1.784-4-4-4h-31c-2.216 0-4 1.784-4 4s1.784 4 4 4h35");
}

</style>
