<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d6okn2m8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pinafore" /></template>
<style>
.d6okn2m8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.443 42.483a17.32 17.32 0 0 1-7.571-10.834l34.256.016a17.6 17.6 0 0 1-7.563 10.814m-19.091.021h19.054M22.291 31.649V5.5M6.977 28.868H19.59V9.833ZM25.166 7.283s15.047 4.945 15.048 21.584h-15.04Z");
}

</style>
