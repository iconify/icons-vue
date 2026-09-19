<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy-mwmbvm"/><circle class="x2q_67o_s"/><circle class="t6wz8cb3t"/><circle class="tqqq13zav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-pending" /></template>
<style>
.t6wz8cb3t {
  cx: 12px;
  cy: 12px;
  r: 1.5px;
  fill: currentColor;
}

.tqqq13zav {
  cx: 17px;
  cy: 12px;
  r: 1.5px;
  fill: currentColor;
}

.vy-mwmbvm {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8");
}

.x2q_67o_s {
  cx: 7px;
  cy: 12px;
  r: 1.5px;
  fill: currentColor;
}

</style>
