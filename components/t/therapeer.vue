<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="xlh6bfj6w"/><path class="fpptwz7fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:therapeer" /></template>
<style>
.fpptwz7fs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.8 41.12l14.06-4.178a2.52 2.52 0 0 0 1.8-2.412V13.47a2.52 2.52 0 0 0-1.8-2.412L10.8 6.88m12.579 19.074v-3.908");
}

.xlh6bfj6w {
  width: 26.419px;
  height: 39px;
  x: 10.79px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.553px;
}

</style>
