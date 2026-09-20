<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cqzimqb1r"/><path class="qmigocc3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swapcard" /></template>
<style>
.cqzimqb1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.32 20.648l-1.601-1.911a8.613 8.613 0 1 0 0 10.527l8.816-10.527a8.615 8.615 0 0 1 14.754 1.91");
}

.qmigocc3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.935 27.353l1.6 1.91a8.615 8.615 0 0 0 14.735-1.868");
}

</style>
