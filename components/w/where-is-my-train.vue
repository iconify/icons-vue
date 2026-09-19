<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nekq3ubky"/><circle class="pv3bupbio"/><circle class="wnfs6lbqq"/><path class="i9mp2zv2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:where-is-my-train" /></template>
<style>
.i9mp2zv2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.349 8.326h3.302M31.11 6.42h-1.686l-.318-.804a1.945 1.945 0 0 0-1.808-1.228h-6.596a1.945 1.945 0 0 0-1.808 1.228l-.318.803H16.89a6.763 6.763 0 0 0-6.764 6.763v16.19a5.936 5.936 0 0 0 5.936 5.936h15.874a5.936 5.936 0 0 0 5.936-5.936v-16.19a6.763 6.763 0 0 0-6.764-6.763M18.824 35.308l-7.177 8.08m22.028-2.934h-19.35m17.044-2.663H16.631m12.545-2.483l7.177 8.08");
}

.nekq3ubky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.325 12.919h19.349v7.854H14.325z");
}

.pv3bupbio {
  cx: 18.146px;
  cy: 28.176px;
  r: 2.528px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wnfs6lbqq {
  cx: 29.889px;
  cy: 28.176px;
  r: 2.528px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
