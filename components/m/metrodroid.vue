<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_ytlfbzg"/><path class="r061o3bzj"/><rect class="nhxj6nbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metrodroid" /></template>
<style>
.nhxj6nbud {
  width: 6.867px;
  height: 9.134px;
  x: 25.016px;
  y: 20.736px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.433px;
  ry: 3.433px;
}

.r061o3bzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.999 21.754l2.925 3.12c.25.221.274.603.053.853l-.005.005l-2.925 3.12M7.872 29.883V16.108l6.875 13.79l6.875-13.769v13.769m10.261-13.762V29.87");
}

.z_ytlfbzg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 8.4h-31a4 4 0 0 0-4 4v23.2a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4V12.4a4 4 0 0 0-4-4");
}

</style>
