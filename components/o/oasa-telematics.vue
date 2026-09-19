<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vd6vlfbgw"/><path class="up4o7_b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oasa-telematics" /></template>
<style>
.up4o7_b1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.468 42.5h9.351V23.16c0-3.005-.75-5.834-2.073-8.31l3.754.002V5.5H23.16C13.406 5.5 5.5 13.406 5.5 23.16s7.906 17.659 17.66 17.659c2.905 0 5.766-.717 8.318-2.082z");
}

.vd6vlfbgw {
  cx: 23.16px;
  cy: 23.159px;
  r: 8.308px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
