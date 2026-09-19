<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><path class="dsupx9ycw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zip-file" /></template>
<style>
.dsupx9ycw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.315 4.5h3.657v2.822h-3.657zm-3.657 2.822h3.657v2.822h-3.657zm3.657 2.821h3.657v2.822h-3.657zm-3.657 2.822h3.657v2.822h-3.657zm3.657 2.821h3.657v2.822h-3.657zm-3.657 2.822h3.657v2.822h-3.657zm3.657 2.821h3.657v2.822h-3.657zm-3.657 2.822h3.657v2.822h-3.657zm3.657 2.821h3.657v2.822h-3.657z");
}

.r4h1y5b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

</style>
