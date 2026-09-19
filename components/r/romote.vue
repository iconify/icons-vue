<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w14fy7blv"/><circle class="zse31e82s"/><path class="r_jsb6b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:romote" /></template>
<style>
.r_jsb6b4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.004 21.639L39.365 24l-2.361 2.361m-26.708 0L7.935 24l2.361-2.361m16.065 15.715L24 39.715l-2.361-2.361m0-26.708L24 8.285l2.361 2.361");
}

.w14fy7blv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 17.21h-7.99a1.72 1.72 0 0 1-1.72-1.72h0V7.5a2 2 0 0 0-2-2h-9.58a2 2 0 0 0-2 2v7.99a1.72 1.72 0 0 1-1.72 1.72H7.5a2 2 0 0 0-2 2v9.58a2 2 0 0 0 2 2h7.99a1.72 1.72 0 0 1 1.72 1.72v7.99a2 2 0 0 0 2 2h9.58a2 2 0 0 0 2-2v-7.99a1.72 1.72 0 0 1 1.72-1.72h7.99a2 2 0 0 0 2-2v-9.58a2 2 0 0 0-2-2");
}

.zse31e82s {
  cx: 24px;
  cy: 24px;
  r: 6.79px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
