<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5h-54bsv"/><circle class="basbx4bcg"/><path class="z5q0embta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photo-editor" /></template>
<style>
.a5h-54bsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24V12.5a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4H24");
}

.basbx4bcg {
  cx: 14.158px;
  cy: 17.169px;
  r: 2.772px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z5q0embta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.875 29.375L14.25 26l5.375 5.375l13.812-13.812l3.688 3.688m2.183 6.189c.959-.804 2.45-.648 3.254.31s.69 2.411-.269 3.215l-1.529-1.79zm-9.57 7.57l9.57-7.57l1.456 1.735l1.53 1.79l-9.545 7.635m-3.012-3.59l-1.54 4.233l4.552-.642");
}

</style>
