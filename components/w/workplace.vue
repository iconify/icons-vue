<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h04retykz"/><path class="m4alzvbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:workplace" /></template>
<style>
.h04retykz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 4.5a3.26 3.26 0 0 0-3.24 3.27V43.5h32.48V10.42h-8.1l-.79-1.62l5.58-1.27l-.52-2.27l-6.12 1.4l-1.06-2.16ZM7.76 37.62h32.48M30.29 6.66l1.06 2.14M7.76 18.44h32.48");
}

.m4alzvbxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.68 18.44h14.65v8.17H16.68z");
}

</style>
