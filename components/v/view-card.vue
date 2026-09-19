<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="d50n78bvr"/><path class="gfzzw8qyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:view-card" /></template>
<style>
.d50n78bvr {
  width: 39px;
  height: 27px;
  x: 4.5px;
  y: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.gfzzw8qyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 32.25h39M16.312 20.188l-2.44 6.623l-2.44-6.623m25.136 0l-2.013 6.623l-2.014-6.623l-2.013 6.623l-2.013-6.623m-9.762 0v6.623m7.002-1.26a2.43 2.43 0 0 1-2.12 1.261c-1.348 0-2.44-1.119-2.44-2.499V22.69c0-1.38 1.092-2.5 2.44-2.5s2.44 1.12 2.44 2.5v.812h-4.88");
}

</style>
