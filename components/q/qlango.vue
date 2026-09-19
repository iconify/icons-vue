<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="y409j3mbp"/><path class="lflbodbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qlango" /></template>
<style>
.lflbodbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24c0-10.217-8.283-18.5-18.5-18.5S5.5 13.783 5.5 24S13.783 42.5 24 42.5h18.5v-7.154h-3.91A18.4 18.4 0 0 0 42.5 24");
}

.y409j3mbp {
  cx: 24px;
  cy: 24px;
  r: 11.346px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
