<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ludndtb7p"/><circle class="cpk0fnbgt"/><circle class="rksdrtbqh"/><path class="s671vypkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vivi" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ludndtb7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.461 17.396l.421.848a12.5 12.5 0 0 1 1.284 4.868a18 18 0 0 1-.203 3.479a10.9 10.9 0 0 1-.886 2.956a13.7 13.7 0 0 1-3.312 4.41a19 19 0 0 1-2.494 1.731l-2.893 1.343a11.87 11.87 0 0 1-9.043-1.002a16.4 16.4 0 0 1-4.445-3.57a12.04 12.04 0 0 1-2.788-5.98a12.28 12.28 0 0 1 .815-7.86a13.5 13.5 0 0 1 5.4-6.119a14.4 14.4 0 0 1 4.87-1.635l.36-.089");
}

.rksdrtbqh {
  cx: 24px;
  cy: 24px;
  r: 5.627px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s671vypkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.625 3.584l-.004 20.748");
}

</style>
