<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dcpfrxg2b"/><circle class="kkr14qbbc"/><circle class="tvcqnzpzp"/><path class="m9nihyy7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:univ-coop" /></template>
<style>
.dcpfrxg2b {
  cx: 18.175px;
  cy: 25.6px;
  r: 5.542px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kkr14qbbc {
  cx: 25.853px;
  cy: 35.272px;
  r: 5.844px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m9nihyy7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.207 12.682c-.356 3.531-3.183 6.323-6.754 6.67s-6.892-1.849-7.935-5.245s.484-7.048 3.647-8.724s7.082-.91 9.363 1.83m-6.519 28.261V43.5");
}

.tvcqnzpzp {
  cx: 29.523px;
  cy: 23.164px;
  r: 5.844px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
