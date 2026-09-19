<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ji847xyjr"/><path class="qmsri0b5d"/><path class="g6mdybbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:posture-reminder" /></template>
<style>
.g6mdybbhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.676 22.237l-3.22 13.296a5.83 5.83 0 0 0 .049 2.93l1.118 4.037M24 16.278v17.343");
}

.ji847xyjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.324 22.237l3.22 13.296a5.83 5.83 0 0 1-.049 2.93L14.377 42.5");
}

.qmsri0b5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.216 41.179l1.668-22.745a5.55 5.55 0 0 0-4.398-5.84l-4.904-1.028a3.51 3.51 0 0 1-2.792-3.439V6.916c0-.782-.634-1.416-1.416-1.416h-6.748c-.782 0-1.415.634-1.415 1.416v1.211a3.51 3.51 0 0 1-2.793 3.439l-4.904 1.028a5.55 5.55 0 0 0-4.397 5.84l1.667 22.745a1.425 1.425 0 0 0 1.421 1.321h27.59c.747 0 1.367-.576 1.421-1.321");
}

</style>
