<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-i-vobfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:next-player" /></template>
<style>
.p-i-vobfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.915 22.987L12.931 6.831a1.17 1.17 0 0 0-1.754 1.012v32.314c0 .9.975 1.462 1.754 1.012l27.984-16.156a1.17 1.17 0 0 0 0-2.026M11.177 8.518L8.254 6.831A1.17 1.17 0 0 0 6.5 7.843v32.314c0 .9.974 1.462 1.754 1.012l2.923-1.687");
}

</style>
