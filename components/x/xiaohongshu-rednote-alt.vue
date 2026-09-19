<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="w1148nbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xiaohongshu-rednote-alt" /></template>
<style>
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

.w1148nbzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 24.061v-9.806h3.21c1.815 0 3.287 1.474 3.287 3.293s-1.472 3.294-3.287 3.294H12.5m3.21 0l3.211 3.217m2.724-4.901h3.197m1.706 4.903h-4.903v-9.806h4.903m2.455 9.806v-9.806h2.207a4.29 4.29 0 0 1 4.29 4.29v1.226a4.29 4.29 0 0 1-4.29 4.29zm-3.26 2.315v6.309c0 .585.475 1.06 1.06 1.06h.318m-2.491-5.619h2.226m-10.115 5.619v-3.499a2.12 2.12 0 0 0-2.12-2.12h0a2.12 2.12 0 0 0-2.12 2.12m-.001 3.499v-5.619m19.998 4.549a2.12 2.12 0 0 1-1.843 1.07h0a2.12 2.12 0 0 1-2.12-2.12v-1.379a2.12 2.12 0 0 1 2.12-2.12h0a2.12 2.12 0 0 1 2.12 2.12v.69h-4.24m-9.56-.69a2.12 2.12 0 0 1 4.241 0v1.379a2.12 2.12 0 0 1-4.241 0z");
}

</style>
