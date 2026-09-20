<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6opo-b3d"/><path class="q3wpe2cqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:turingmachine" /></template>
<style>
.q3wpe2cqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.79 14.25H14.44a9.16 9.16 0 0 0-9.16 9.16a9.3 9.3 0 0 0 .23 2.06");
}

.q6opo-b3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 33.75l9.71 7.93V25.83zm9.71 0h19.35a9.16 9.16 0 0 0 9.16-9.16a9.3 9.3 0 0 0-.23-2.06m1.01-8.28l-9.71-7.93v15.85z");
}

</style>
