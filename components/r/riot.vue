<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cbmtvfzqz"/><path class="zaqsx61ep"/><circle class="yk_riq4ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:riot" /></template>
<style>
.cbmtvfzqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.32 29.35A12.4 12.4 0 0 0 36 27.7a14.2 14.2 0 0 0 3.55-9.27A13.93 13.93 0 0 0 25.62 4.5H14m-5.55 5.57v27.86a5.57 5.57 0 1 0 11.14 0V26");
}

.yk_riq4ka {
  cx: 14.02px;
  cy: 10.07px;
  r: 5.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zaqsx61ep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.2 20.47a5.57 5.57 0 0 0-4.56 8.77L29 41.13a5.57 5.57 0 0 0 9.12-6.38l-8.36-11.91a5.55 5.55 0 0 0-4.56-2.38Z");
}

</style>
