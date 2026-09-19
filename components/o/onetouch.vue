<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="l3vagbb4b"/><path class="nc5br2wvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:onetouch" /></template>
<style>
.l3vagbb4b {
  cx: 28.593px;
  cy: 19.183px;
  r: 13.052px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nc5br2wvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.645 23.746c1.859 9.807 9.578 17.526 19.385 19.384");
}

</style>
