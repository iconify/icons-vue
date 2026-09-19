<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="j-x7i0vvz"/><path class="alfjanb4e"/><path class="snbsokb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sncb" /></template>
<style>
.alfjanb4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.888 16.546v15.176m-3.646-13.734a14.6 14.6 0 0 1 8.478-2.459c3.476 0 5.596 1.993 5.596 4.07s-1.95 3.9-5.002 3.9h-5.426");
}

.j-x7i0vvz {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 13.473px;
}

.snbsokb9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.242 29.857a13.63 13.63 0 0 0 8.083 2.798c3.702 0 7.432-1.4 7.432-4.748s-3.222-4.409-6.443-4.409");
}

</style>
