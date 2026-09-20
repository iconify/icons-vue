<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b8cri2elt"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocketrx" /></template>
<style>
.b8cri2elt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.126 25.554l4.912 7.415m0-7.415l-4.912 7.415m-6.626 0v-7.415h2.428c1.372 0 2.484 1.115 2.484 2.49s-1.112 2.49-2.485 2.49H9.5m2.428 0l2.427 2.433M9.5 22.446v-7.415h2.428c1.372 0 2.484 1.115 2.484 2.49s-1.112 2.49-2.485 2.49H9.5m16.97-4.98v7.415m.001-1.575l3.356-3.34m-2.288 2.277l2.639 2.627m7.117-6.431v5.515c0 .512.415.927.927.927h.278m-2.178-4.912h1.946m-13.57 3.978a1.854 1.854 0 0 1-3.463-.92v-1.205a1.853 1.853 0 0 1 3.462-.923m10.197 3.046a1.854 1.854 0 0 1-3.464-.918v-1.205a1.854 1.854 0 0 1 3.707 0v.603h-3.708m-15.696-.603a1.854 1.854 0 1 1 3.707 0v1.205a1.854 1.854 0 1 1-3.708 0z");
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
