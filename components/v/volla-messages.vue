<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xw_um96eh"/><circle class="t51n1yb2w"/><circle class="e2hppc56o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:volla-messages" /></template>
<style>
.e2hppc56o {
  cx: 24px;
  cy: 29px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t51n1yb2w {
  cx: 24px;
  cy: 19px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xw_um96eh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5c-2.216 0-4-1.784-4-4V24C5.5 13.783 13.783 5.5 24 5.5S42.5 13.783 42.5 24S34.217 42.5 24 42.5z");
}

</style>
