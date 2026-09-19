<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ybuwyomsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nate" /></template>
<style>
.ybuwyomsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.4 24v17.267h11.1V21.533q0-14.8-14.8-14.8H5.5v34.534h11.1V17.833h8.633q6.167 0 6.167 6.167");
}

</style>
