<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="d57hfkbuu"/><circle class="pszbg-cib"/><path class="rlb0a05cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stario-launcher" /></template>
<style>
.d57hfkbuu {
  cx: 35.393px;
  cy: 15.893px;
  r: 8.107px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pszbg-cib {
  cx: 12.607px;
  cy: 32.107px;
  r: 8.107px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rlb0a05cd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.607 24a8.107 8.107 0 0 1 0-16.213h15.775a8.107 8.107 0 0 0 0 16.213h7.011a8.107 8.107 0 0 1 0 16.213H19.618a8.107 8.107 0 0 0 0-16.213z");
}

</style>
