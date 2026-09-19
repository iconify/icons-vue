<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ocd99yb9j"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openscale" /></template>
<style>
.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.ocd99yb9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.5 17.5l-3.7 3.7l-1.2 1.2c-.8.8-2.1.8-3 0q0 0 0 0c-2.5-2.5-6.6-2.5-9.1 0q0 0 0 0c-.8.8-2.1.8-3 0q0 0 0 0l-1.2-1.2l-3.7-3.7c-.8-.8-.8-2.2 0-3q0 0 0 0c6.9-6.9 18-6.9 24.9 0q0 0 0 0c.9.8.9 2.1 0 3q0 0 0 0M19 14.9l3.6 5.8");
}

</style>
