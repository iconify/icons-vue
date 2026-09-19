<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8eajpbrl"/><path class="kwhzuubbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openwrt" /></template>
<style>
.kwhzuubbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.443 11.944c8.592-8.592 22.522-8.592 31.113 0q0 0 0 0m-21.213 9.899a8 8 0 0 1 11.314 0h0M26 27.5a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.s8eajpbrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.99 20a15 15 0 0 1-22.633 18.99A15 15 0 0 1 11.01 20m2.383-3.107c5.858-5.858 15.355-5.858 21.213 0");
}

</style>
