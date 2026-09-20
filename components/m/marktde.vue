<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ymrom-bcz"/><path class="snjlxw2vx"/><path class="aq0iq8gte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:marktde" /></template>
<style>
.aq0iq8gte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.73 24.13a2 2 0 0 1 2-2a2 2 0 0 1 2 2v3.13M26.08 24a2 2 0 0 1 2-2m-2 .08v5.18m3.42-7.83v7.83m0-1.66l3.54-3.53m-2.41 2.41l2.78 2.77m-9.12-1.95a2 2 0 0 1-1.95 2a2 2 0 0 1-2-2V24a2 2 0 0 1 2-2a2 2 0 0 1 1.95 2m0 3.26v-5.18m11.62-1.62v5.82a1 1 0 0 0 1 1h.3m-2.33-5.2h2.05");
}

.snjlxw2vx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.82 24.13a2 2 0 0 1 2-2a2 2 0 0 1 2 2v3.13m-4-5.09v5.09");
}

.ymrom-bcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.78 8.56L32.6 5.67a6.71 6.71 0 0 1 7.68 6l2.31 25a5 5 0 0 1-5.39 5.47l-24.64-1.93a7.53 7.53 0 0 1-6.87-8.56l2.47-17.41a6.7 6.7 0 0 1 5.62-5.68");
}

</style>
