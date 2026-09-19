<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ht8jl5_2g"/><path class="de3smmbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobilizon" /></template>
<style>
.de3smmbwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.28 29.29c0 6-1.49 9.31-5.4 9.29c-3.49 0-5.11-3.4-5.13-9.28c0-6.18 2-9.19 5.23-9.29c3-.1 5.35 2.74 5.31 9.28Z");
}

.ht8jl5_2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.82 7.67c-.08 2.87-.63 3.55-3.66 3.54c-2.88 0-4-.62-3.94-3.48c0-2.65.78-3.1 3.72-3.15c3.12-.04 3.95.67 3.88 3.09M36 29.16c.05 8.66-4.83 14.54-12.18 14.42c-6.53-.09-11.82-5-11.82-14.42s4.46-14 11.94-14.29S36 20.15 36 29.16");
}

</style>
