<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhjky3bhc"/><path class="a511ixfis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:presently" /></template>
<style>
.a511ixfis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.368 29.894c1.904 7.011 6.181 10.37 9.223 12.606");
}

.xhjky3bhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.368 29.894c2.622-.43 9.557.868 6.83-10.412C30.471 8.203 21.088 11.935 18.354 5.5c-6.372 11.408-7.102 15.27-4.63 21.965c1.604 4.34 8.916 7.391 12.644 2.428Z");
}

</style>
