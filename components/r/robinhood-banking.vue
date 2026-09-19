<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z20c8hbnk"/><path class="yorf2eboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:robinhood-banking" /></template>
<style>
.yorf2eboh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.647 14.903l8.346-8.962s7.414-3.242 10.74 0c2.669 2.6.754 7.867.754 7.867c-4.173 4.858-9.236 11.7-12.041 18.54l-12.71 3.518m16.61-23.494l-1.307 14.672");
}

.z20c8hbnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.848 43.5c1.697-9.276 15.676-27.632 19.498-31.128l-11.7 2.53L10.6 24.14s.842 4.986 2.546 10.935");
}

</style>
