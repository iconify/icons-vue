<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cmaf3551r"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:obimy" /></template>
<style>
.cmaf3551r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.1 31.75c-1.6 1.5-3.7 2.4-5.9 2.4s-4.4-.9-6-2.4m3.9-13.7c-1.4-1.4-3.3-2.2-5.3-2.2c-1.9 0-3.8.8-5.2 2.1m24.8.1c-1.4-1.4-3.3-2.2-5.3-2.2c-1.9 0-3.8.8-5.2 2.1");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

</style>
