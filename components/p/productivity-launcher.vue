<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y5lqk2b3i"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:productivity-launcher" /></template>
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

.y5lqk2b3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 30.802c2.28-2.64 5.353-5.374 8.25-4.768c3.702.775 4.508 6.462 6.91 6.322c3.408-.2 4.453-11.795 8.197-11.947c1.436-.058 1.931 1.621 3.643 1.661c2.496.058 4.603-3.44 6-6.429");
}

</style>
