<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xj0oqnn9p"/><path class="swulkgxbm"/><path class="mzanbpxfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:peak" /></template>
<style>
.mzanbpxfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.25A9.25 9.25 0 0 1 33.25 24h9.25a9.25 9.25 0 0 1-9.25 9.25a9.25 9.25 0 0 1 9.25 9.25H14.75v-37H5.5v27.75M33.25 24v18.5");
}

.swulkgxbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.75h9.25l6.54 6.54a9.25 9.25 0 1 1 2.71-6.54zm0 27.75v-9.25A9.25 9.25 0 0 0 14.75 24a9.25 9.25 0 0 1-9.25 9.25a9.25 9.25 0 0 0 9.25 9.25");
}

.xj0oqnn9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 5.5a9.25 9.25 0 0 1 0 18.5");
}

</style>
