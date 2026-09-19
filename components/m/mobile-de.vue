<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b27plwb2x"/><path class="y37eeubdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobile-de" /></template>
<style>
.b27plwb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4m-22.6.3v36.4m4.8-23.8v11.2");
}

.y37eeubdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.7 22.629a4.225 4.225 0 0 1 4.225-4.225h0a4.225 4.225 0 0 1 4.225 4.225V29.6M20.7 18.404V29.6m8.45-6.971a4.225 4.225 0 0 1 4.225-4.225h0a4.225 4.225 0 0 1 4.225 4.225V29.6");
}

</style>
