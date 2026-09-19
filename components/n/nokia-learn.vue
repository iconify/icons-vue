<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xnrlheksi"/><path class="alj_n-nhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nokia-learn" /></template>
<style>
.alj_n-nhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.191 22.748a2.165 2.165 0 1 1 0-4.33H43.5v4.33zm0 6.833a2.165 2.165 0 1 1 0-4.33H43.5v4.33z");
}

.xnrlheksi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.897 32.205a8.205 8.205 0 0 1 0-16.41H43.5v-4.32H17.025C10.108 11.475 4.5 17.083 4.5 24s5.608 12.525 12.525 12.525H43.5v-4.32z");
}

</style>
