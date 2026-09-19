<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iu024yxsz"/><path class="xvbushfmc"/><path class="p0_-etbwz"/><path class="x286t9bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:waymo-one" /></template>
<style>
.iu024yxsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.394 34.737a3.28 3.28 0 0 1-2.844-1.641L3.94 18.184a3.28 3.28 0 1 1 5.681-3.28l8.61 14.912a3.28 3.28 0 0 1-2.837 4.921m17.219 0a3.28 3.28 0 0 1-2.844-1.641l-8.61-14.912a3.28 3.28 0 1 1 5.681-3.28l8.61 14.912a3.28 3.28 0 0 1-2.837 4.921M24 23.104l-5.77 9.992m-2.84-8.2l5.77-9.992");
}

.p0_-etbwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.379 14.904a3.28 3.28 0 1 1 5.68 3.28");
}

.x286t9bhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.06 18.184a3.28 3.28 0 1 1-5.68-3.28");
}

.xvbushfmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.642 24.84l5.737-9.936a3.28 3.28 0 1 1 5.68 3.28L35.45 33.096");
}

</style>
