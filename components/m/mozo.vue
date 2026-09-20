<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ik-udbckb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mozo" /></template>
<style>
.ik-udbckb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 23.324a2.08 2.08 0 0 1 4.159 0v3.431m-4.159-5.51v5.51m4.159-3.431a2.08 2.08 0 0 1 4.159 0v3.431m8.306-5.51h4.159l-4.159 5.51h4.159m-10.375-3.431a2.08 2.08 0 0 1 4.158 0v1.352a2.08 2.08 0 0 1-4.158 0zm12.433 0a2.08 2.08 0 0 1 4.159 0v1.352a2.08 2.08 0 0 1-4.159 0z");
}

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

</style>
