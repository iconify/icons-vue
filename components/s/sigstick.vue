<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pgvaqkgqj"/><path class="hpehkl33y"/><path class="ldvgv8p3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sigstick" /></template>
<style>
.hpehkl33y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 5.5c-5.54 0-10 4.46-10 10v17c0 5.54 4.46 10 10 10h12.199L42.5 27.699V15.5c0-5.54-4.46-10-10-10z");
}

.ldvgv8p3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.278 22.02a2.5 2.5 0 0 1 5 0m18.444 0a2.5 2.5 0 0 0-5 0M19 25.846a2.5 2.5 0 0 0 5 0m0 0a2.5 2.5 0 0 0 5 0");
}

.pgvaqkgqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.699 42.5L42.5 27.699h-4.8c-5.54 0-10 4.46-10 10z");
}

</style>
