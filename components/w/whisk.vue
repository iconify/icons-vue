<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h9zoefbrx"/><path class="da0ks0b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whisk" /></template>
<style>
.da0ks0b5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.826 22.643c.299-10.557-7.991-10.74-8.656-10.737c-6.384.021-7.71 6.533-4.91 8.223c4.783 2.887 10.926-9.092 1.529-13.66c-3.606-1.753-6.582-.607-9.477 1.25");
}

.h9zoefbrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 23.726zC42.5 34.04 34.14 42.4 23.826 42.4A18.675 18.675 0 0 1 5.5 27.316l36.802-6.295q.197 1.346.197 2.706z");
}

</style>
