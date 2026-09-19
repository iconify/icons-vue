<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tl7k2u8sv"/><path class="h1b0u6jlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whatsappbusiness" /></template>
<style>
.h1b0u6jlb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.517 21.517 0 0 0 5.148 34.36L2.5 45.5l11.14-2.648A21.504 21.504 0 1 0 24 2.5Z");
}

.tl7k2u8sv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.95 24a6 6 0 1 1 0 12h-9.9V12h9.9a6 6 0 1 1 0 12Zm-.081 0h-9.488");
}

</style>
