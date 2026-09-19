<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g1ya29duh"/><path class="w6tjgxuyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:poet-assistant" /></template>
<style>
.g1ya29duh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.063 4.5h-3a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4h3m0-39v39h20a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4z");
}

.w6tjgxuyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.766 29.5v-11h3.6c2.037 0 3.687 1.654 3.687 3.694s-1.65 3.694-3.686 3.694h-3.602m14.55-.032h-4.873M28.235 29.5l3.643-11l3.644 11");
}

</style>
