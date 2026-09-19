<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="afhptwb_j"/><path class="ypeq5ubbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meme-generator" /></template>
<style>
.afhptwb_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.48 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29.04a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.ypeq5ubbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 26.736v-3.367c0-1.162.942-2.105 2.104-2.105h0c1.163 0 2.105.942 2.105 2.105v3.367m0-3.367c0-1.162.942-2.105 2.104-2.105h0c1.162 0 2.105.942 2.105 2.105v3.367m5.806-1.01a2.1 2.1 0 0 1-1.829 1.062h0a2.104 2.104 0 0 1-2.104-2.104v-1.368c0-1.162.942-2.104 2.104-2.104h0c1.162 0 2.104.942 2.104 2.104V24h-4.208M25 26.736v-3.367c0-1.162.943-2.105 2.105-2.105h0c1.162 0 2.104.942 2.104 2.105v3.367m.001-3.367c0-1.162.941-2.105 2.104-2.105h0c1.162 0 2.104.942 2.104 2.105v3.367m5.806-1.01a2.1 2.1 0 0 1-1.828 1.062h0a2.104 2.104 0 0 1-2.105-2.104v-1.368c0-1.162.942-2.104 2.105-2.104h0c1.162 0 2.104.942 2.104 2.104V24h-4.209");
}

</style>
