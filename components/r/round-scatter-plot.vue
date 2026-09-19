<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="yg3x3ublv"/><circle class="ap76noi5m"/><circle class="sjg9j274c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-scatter-plot" /></template>
<style>
.ap76noi5m {
  cx: 11px;
  cy: 6px;
  r: 3px;
  fill: currentColor;
}

.sjg9j274c {
  cx: 16.6px;
  cy: 17.6px;
  r: 3px;
  fill: currentColor;
}

.yg3x3ublv {
  cx: 7px;
  cy: 14px;
  r: 3px;
  fill: currentColor;
}

</style>
