<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="y9wy7ob-z"/><circle class="ibzr30qxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shpock" /></template>
<style>
.ibzr30qxg {
  cx: 34.98px;
  cy: 13.021px;
  r: 7.52px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9wy7ob-z {
  cx: 20.24px;
  cy: 27.76px;
  r: 14.74px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
