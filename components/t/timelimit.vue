<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihkt6zigk"/><path class="u-aul108h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:timelimit" /></template>
<style>
.ihkt6zigk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.14 24L9 32.24a16.37 16.37 0 1 0 14.14-24.6Z");
}

.u-aul108h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5A21.5 21.5 0 1 1 45.5 24A21.51 21.51 0 0 1 24 45.5");
}

</style>
