<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="km7oiubeq"/><rect transform="rotate(-45 24 24.001)" class="qbmlrr9wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:npo" /></template>
<style>
.km7oiubeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.112 15.066a2.545 2.545 0 0 1-3.599 0l-1.174-1.174a2.545 2.545 0 1 1 3.6-3.6l1.173 1.175a2.545 2.545 0 0 1 0 3.599m-5.82 5.821a2.545 2.545 0 0 1-3.599 0l-1.174-1.174a2.545 2.545 0 1 1 3.6-3.6l1.173 1.174a2.545 2.545 0 0 1 0 3.6M17.28 24.9l-1.464-1.462l-1.174-1.174a2.545 2.545 0 1 0-3.6 3.6L13.68 28.5m2.84-8.79l5.41 5.4");
}

.qbmlrr9wz {
  width: 30px;
  height: 30px;
  x: 9px;
  y: 9.001px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

</style>
