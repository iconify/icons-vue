<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r31p6nbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifi" /></template>
<style>
.r31p6nbhh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.765 28.616a10.516 10.516 0 0 0-13.435-.037v.037m6.691 4.305a4.216 4.216 0 1 0 4.216 4.216a4.216 4.216 0 0 0-4.216-4.216m13.157-11.595a20.676 20.676 0 0 0-26.314 0M43.5 13.674a30.57 30.57 0 0 0-39 0");
}

</style>
