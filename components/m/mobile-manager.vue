<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vqnafzcik"/><circle class="a9ts1mjmt"/><path class="ha7sxbclx"/><circle class="a9ts1mjmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobile-manager" /></template>
<style>
.a9ts1mjmt {
  cx: 24px;
  cy: 33.675px;
  r: 2.707px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ha7sxbclx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.702 30.968l3.108-11.129m-13.735 1.504c0-5.514 4.41-9.925 9.925-9.925s9.925 4.411 9.925 9.925M24 11.518v2.406m-9.925 7.419h2.406m17.444 0h-2.406");
}

.vqnafzcik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c1.704 0 15.24-7.82 15.24-16.943V6.505C35.228 6.505 24 4.5 24 4.5S12.671 6.505 8.76 6.505v20.052C8.76 35.68 22.297 43.5 24 43.5");
}

</style>
