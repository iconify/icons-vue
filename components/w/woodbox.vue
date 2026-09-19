<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vxre9xbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:woodbox" /></template>
<style>
.vxre9xbgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.748 4.838l6.237 7.484a.998.998 0 0 1-.748 1.497h-3.243l6.985 8.981a.998.998 0 0 1-.748 1.497h-5.739l9.98 11.975a.998.998 0 0 1-.749 1.497H11.277a.998.998 0 0 1-.749-1.497l9.98-11.975h-5.739a.998.998 0 0 1-.748-1.497l6.985-8.98h-3.243a.998.998 0 0 1-.748-1.498l6.237-7.484a.998.998 0 0 1 1.497 0m2.245 32.931v4.733a1 1 0 0 1-.998.998h-3.992a1 1 0 0 1-.998-.998V37.77");
}

</style>
