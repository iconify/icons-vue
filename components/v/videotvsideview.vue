<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zl6rn2spx"/><path class="vdxw4_bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:videotvsideview" /></template>
<style>
.vdxw4_bee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 14.64h7.13l4.08 7.19l4.63-10.35");
}

.zl6rn2spx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.14 24.81v11.71h31.7V14.64H21.75m21.75 0v21.88m-4.66-19.66h4.66m-4.66 4.36h4.66m-4.66 4.36h4.66m-4.66 4.36h4.66m-4.66 4.36h4.66M7.14 21.83V11.48");
}

</style>
