<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfmg3_v0y"/><rect class="jc1oydeao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qld-rego-check" /></template>
<style>
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

.vfmg3_v0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.1 16v4.5h2.2m2.4 0V16h1c1.1 0 2 .9 2 2v.6c0 1.1-.9 2-2 2h-1zm-7.4 0L18.9 19m0-3a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5h0a1.5 1.5 0 0 1-1.5-1.5v-1.5a1.5 1.5 0 0 1 1.5-1.5m-7.1 15.1v-7.2h2.4c1.3 0 2.4 1.1 2.4 2.4s-1.1 2.4-2.4 2.4h-2.4m2.3 0l2.4 2.4m2.4-3.6h2.3m1.3 3.6h-3.6v-7.2h3.6m11.3 0a2.4 2.4 0 0 1 2.4 2.4v2.4a2.4 2.4 0 0 1-2.4 2.4h0a2.4 2.4 0 0 1-2.4-2.4v-2.4a2.4 2.4 0 0 1 2.4-2.4m-4.5 2.4c0-1.3-1.1-2.4-2.4-2.4h0c-1.3 0-2.4 1.1-2.4 2.4v2.4c0 1.3 1.1 2.4 2.4 2.4h0c1.3 0 2.4-1.1 2.4-2.4h-2.4");
}

</style>
