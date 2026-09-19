<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="id4h8x_qn"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vpnh" /></template>
<style>
.id4h8x_qn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.354 28.12v-8.24h2.698c1.525 0 2.762 1.239 2.762 2.767s-1.237 2.768-2.762 2.768h-2.698m7.773 2.705v-8.24l5.459 8.24v-8.24m2.454 0v8.24m5.46-8.24v8.24m-5.46-4.135h5.46M14.96 19.88l-2.73 8.24l-2.73-8.24");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

</style>
