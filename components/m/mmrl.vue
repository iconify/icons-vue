<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wb6j3_bae"/><path class="tpgtxt4oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mmrl" /></template>
<style>
.tpgtxt4oc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.765 13.857l.006 20.51L24.24 44.5");
}

.wb6j3_bae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.765 13.857L24.24 24.523V44.5l17.995-10.39V14.14L23.808 3.5zm9.238 5.333L33.022 8.82M24.24 24.523l17.995-10.384");
}

</style>
