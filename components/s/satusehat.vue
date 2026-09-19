<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fwik4lbub"/><circle class="v8cxm8n7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:satusehat" /></template>
<style>
.fwik4lbub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24H9.41c-1.818 0-3.47-1.232-3.83-3.014a3.813 3.813 0 0 1 3.729-4.604h7.073V9.41c0-1.817 1.233-3.468 3.014-3.828A3.813 3.813 0 0 1 24 9.309zm0 0V9.41c0-1.818 1.232-3.47 3.014-3.83a3.813 3.813 0 0 1 4.604 3.729v7.073h6.973c1.817 0 3.468 1.233 3.828 3.014A3.813 3.813 0 0 1 38.692 24zm0 0h14.59c1.818 0 3.47 1.232 3.83 3.014a3.813 3.813 0 0 1-3.729 4.604h-7.073v6.973c0 1.817-1.233 3.468-3.014 3.828A3.813 3.813 0 0 1 24 38.692zm0 0v14.59c0 1.818-1.232 3.47-3.014 3.83a3.813 3.813 0 0 1-4.604-3.729v-7.073H9.41c-1.817 0-3.468-1.233-3.828-3.014A3.813 3.813 0 0 1 9.309 24z");
}

.v8cxm8n7m {
  cx: 10px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
