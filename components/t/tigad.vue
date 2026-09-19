<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9pqv6blq"/><path class="pljhhxjri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tigad" /></template>
<style>
.pljhhxjri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.433 32.209l6.374-11.039l6.375 11.039zm6.375-21.799h-5.616L5.5 37.59h5.616");
}

.w9pqv6blq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.808 10.41L11.116 37.59H42.5z");
}

</style>
