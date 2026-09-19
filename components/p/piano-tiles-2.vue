<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b7dd3l3tt"/><rect class="jc1oydeao"/><path class="adj-zk_bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:piano-tiles-2" /></template>
<style>
.adj-zk_bx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.5v31M4.5 24h39");
}

.b7dd3l3tt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.47 15.07a2.653 2.653 0 0 1 3.176-2.6c1.111.214 1.999 1.175 2.11 2.302c.082.837-.183 1.664-.762 2.172c-1.072.94-4.524 3.476-4.524 3.476h5.3");
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
