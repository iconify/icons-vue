<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uw9003noq"/><path class="vztd8eb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-onenote" /></template>
<style>
.uw9003noq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.8 18.5v11m7.4 0v-11m-7.4 0l7.4 11M5.5 16v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V16c0-1.1-.9-2-2-2h-16c-1.1 0-2 .9-2 2");
}

.vztd8eb3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.2 14V8.5c0-2.2 1.8-4 4-4h21.3c2.2 0 4 1.8 4 4v31c0 2.2-1.8 4-4 4H17.2c-2.2 0-4-1.8-4-4V34");
}

</style>
