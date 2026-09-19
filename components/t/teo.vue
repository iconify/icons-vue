<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="w7q87n73s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:teo" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.w7q87n73s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.65 20h-5.3l3.975 4l-3.975 4h5.3m-14.406-8h5.3m-2.65 8v-8m18.212 0a2.65 2.65 0 0 1 2.65 2.65v2.7a2.65 2.65 0 0 1-2.65 2.65h0a2.65 2.65 0 0 1-2.65-2.65v-2.7a2.65 2.65 0 0 1 2.65-2.65");
}

</style>
