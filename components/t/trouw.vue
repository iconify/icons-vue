<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w-l0jgbjr"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trouw" /></template>
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

.w-l0jgbjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 19.644h5.772M9.85 28.356l1.536-8.712m28.114 2.94l-2.815 5.772l-.779-5.772l-2.814 5.772l-.78-5.772m-6.779 0l-.633 3.594c-.212 1.203.59 2.178 1.794 2.178c1.203 0 2.35-.975 2.562-2.178l.634-3.594m-.634 3.594l-.384 2.178m-14.505-3.594c.212-1.203 1.36-2.178 2.562-2.178m-2.178 0l-1.018 5.772m4.637-3.594c.212-1.203 1.36-2.178 2.562-2.178s2.007.975 1.795 2.178l-.25 1.416c-.212 1.203-1.36 2.178-2.562 2.178s-2.006-.975-1.794-2.178z");
}

</style>
