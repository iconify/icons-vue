<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z01djac8h"/><circle class="hdxf0lbee"/><circle class="zc-bdbc7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ovela" /></template>
<style>
.hdxf0lbee {
  cx: 24px;
  cy: 20.79px;
  r: 9.864px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z01djac8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.96 31.75c6.053-6.053 6.053-15.867 0-21.92s-15.867-6.053-21.92 0s-6.053 15.867 0 21.92A15.45 15.45 0 0 0 24 36.29v6.42z");
}

.zc-bdbc7w {
  cx: 24px;
  cy: 20.79px;
  r: 4.227px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
