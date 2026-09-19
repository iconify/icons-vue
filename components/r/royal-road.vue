<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ldah3abyx"/><path class="vk9gcebqs"/><path class="sidpr9yzv"/><path class="vzlucss_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:royal-road" /></template>
<style>
.ldah3abyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.638 42.5c-11.233-21.136-28.28-22.17-33.354-37c-.937 2.266-4.82 12.177 7.439 19.855c9.36 5.863 13.253 7.144 19.067 17.145z");
}

.sidpr9yzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.79 42.5h-8.622c-3.646 0-10.79-2.933-12.958-9.202m20.488-2.055c3.702-1.98 7.333-5.366 7.333-11.012c0-11.563-9.957-12.383-15.967-12.383H9.237");
}

.vk9gcebqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.402 38.722C19.714 31.218 9.96 40.677 6.362 20.23c3.794 5.222 8.868 4.79 13.02 7.37");
}

.vzlucss_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.904 13.32h12.16c8.564 0 9.395 4.04 9.395 6.91c0 3.82-2.495 6.01-4.65 7.194");
}

</style>
