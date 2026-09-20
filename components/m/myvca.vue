<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="fa9nnb2ci"/><path class="hff50nbwr"/><path class="dkg2yx5ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myvca" /></template>
<style>
.dkg2yx5ln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.745 23.44a1.723 1.723 0 0 1 3.447 0v2.844m10.846-6.894l-2.284 6.894l-2.283-6.894m10.427 4.582V24a2.284 2.284 0 1 1-4.567 0v-2.327a2.284 2.284 0 1 1 4.567 0v.028M37.946 24h-3.054m-.757 2.284l2.284-6.894l2.283 6.894");
}

.fa9nnb2ci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.35 24.56v2.327a1.723 1.723 0 0 1-2.942 1.218");
}

.hff50nbwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.35 21.717v2.843a1.723 1.723 0 1 1-3.447 0v-2.843M9.298 23.44a1.723 1.723 0 0 1 3.447 0v2.844m-3.447-4.568v4.568");
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
