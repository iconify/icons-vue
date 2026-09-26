<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rzgb86cfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-a-16-regular" /></template>
<style>
.rzgb86cfw {
  fill: currentColor;
  d: path("M12 1a.5.5 0 0 1 0 1h-1v12h1a.5.5 0 0 1 0 1H9a.5.5 0 0 1 0-1h1V2H9a.5.5 0 0 1 0-1zM9 4H3.5A1.5 1.5 0 0 0 2 5.5v5A1.5 1.5 0 0 0 3.5 12H9v1H3.5A2.5 2.5 0 0 1 1 10.5v-5A2.5 2.5 0 0 1 3.5 3H9zm3.5-1A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5H12v-1h.5a1.5 1.5 0 0 0 1.5-1.5v-5A1.5 1.5 0 0 0 12.5 4H12V3zM6 4.75a.5.5 0 0 1 .456.295l2.25 5a.5.5 0 0 1-.912.41L7.14 9H4.86l-.654 1.455a.5.5 0 0 1-.912-.41l2.25-5A.5.5 0 0 1 6 4.75M5.31 8h1.38L6 6.468z");
}

</style>
