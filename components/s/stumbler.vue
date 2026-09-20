<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swxqtxb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stumbler" /></template>
<style>
.swxqtxb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.19 12C9.87 7.35 16.65 4.5 24 4.5S38.13 7.35 41.81 12m-27.92 7c2.11-2.48 5.9-4 10.05-4s8 1.5 10.05 3.95m-10.05 4.51a7.38 7.38 0 0 0-6.06 11.6l6.06 8.44l6-8.44a7.38 7.38 0 0 0-6-11.6m0 4.92a2.46 2.46 0 0 1 2.46 2.46a2.46 2.46 0 0 1-2.46 2.46a2.47 2.47 0 0 1-2.47-2.46a2.47 2.47 0 0 1 2.47-2.46");
}

</style>
