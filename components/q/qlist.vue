<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u41wb1bwa"/><circle class="jamt8t__f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qlist" /></template>
<style>
.jamt8t__f {
  cx: 24px;
  cy: 24px;
  r: 11.629px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u41wb1bwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5c10.217 0 18.5 8.283 18.5 18.5v18.5H24C13.783 42.5 5.5 34.217 5.5 24S13.783 5.5 24 5.5");
}

</style>
