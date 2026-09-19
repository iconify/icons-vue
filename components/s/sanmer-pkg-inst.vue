<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-b7nhb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sanmer-pkg-inst" /></template>
<style>
.z-b7nhb4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.437 39.718V10.435h-4.62a2.316 2.316 0 1 1-.001-4.632h32.368a2.316 2.316 0 1 1 0 4.632q0 0 0 0h-4.632v29.283a2.316 2.316 0 1 1-4.621 0l.332-29.283H17.058v29.283a2.316 2.316 0 1 1-4.621 0");
}

</style>
