<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="n919egbim"/><path class="qys1fz7lx"/><circle class="aqj0oqiek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:router-keygen" /></template>
<style>
.aqj0oqiek {
  cx: 24px;
  cy: 31.441px;
  r: 1.423px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n919egbim {
  cx: 12.902px;
  cy: 36.332px;
  r: 3.029px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qys1fz7lx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.126 42.11v-5.778h0h-22.195m18.404 3.331v-3.331m-3.917-9.599a9.976 9.976 0 0 0-12.746-.035v.035m18.831-6.916a19.615 19.615 0 0 0-24.966 0m30.963-7.26a29 29 0 0 0-37 0");
}

</style>
