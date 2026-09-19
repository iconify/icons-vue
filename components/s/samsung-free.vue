<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dplzjsb4y"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-free" /></template>
<style>
.dplzjsb4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.7 28.7h4.7m-4.7-9.4h4.7M25.7 24h4.7m2.4 4.7h4.7m-4.7-9.4h4.7M32.8 24h4.7m-27-4.7h4.7M10.5 24h3.1m-3.1-4.7v9.4m6.9 0v-9.4h3.1c1.7 0 3.2 1.4 3.2 3.2s-1.4 3.2-3.2 3.2h-3.1m3.1-.1l3 3.1");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

</style>
