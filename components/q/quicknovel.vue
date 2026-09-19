<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oo2r56nnz"/><path class="c-f7jpbiv"/><path class="w6ifwq5kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quicknovel" /></template>
<style>
.c-f7jpbiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.944 41.592v-26.92A35 35 0 0 1 43.5 6.407v27.37M23.944 14.673A34.8 34.8 0 0 0 4.5 6.406");
}

.oo2r56nnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 30.861a32.37 32.37 0 0 0-19.556 7.802A32.15 32.15 0 0 0 4.5 30.86");
}

.w6ifwq5kv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.944 41.592A32.34 32.34 0 0 1 43.5 33.776M4.5 6.407v27.37m19.444 7.817A32.1 32.1 0 0 0 4.5 33.776");
}

</style>
