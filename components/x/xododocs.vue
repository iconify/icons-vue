<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qs52qlbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xododocs" /></template>
<style>
.qs52qlbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.11 25.24V10s-12.83 1.65-12.83 6.33c0 5.06 18.22 7.75 18.22 7.75V40s-18.22-2.47-18.22-8.3c0-3.86 12.83-6.46 12.83-6.46M9.89 22.76V38s12.83-1.65 12.83-6.33c0-5.06-18.22-7.75-18.22-7.75V8.05s18.22 2.47 18.22 8.3c0 3.81-12.83 6.41-12.83 6.41");
}

</style>
