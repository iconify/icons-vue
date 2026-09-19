<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_fchn7gk"/><rect class="he0p_ybwu"/><path class="nbq9m2-fr"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wie-is-de-mol" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d_fchn7gk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.488 14.934v17h4m-21.591-.009V14.934l4 17l4-16.988v16.988");
}

.he0p_ybwu {
  width: 5.3px;
  height: 17px;
  x: 29.029px;
  y: 14.934px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.nbq9m2-fr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.953 27.066h2.57m.925 6h-3.495v-12h3.495m-8.936 12v-12h1.04a2.26 2.26 0 0 1 2.26 2.26v7.479a2.26 2.26 0 0 1-2.26 2.26z");
}

</style>
