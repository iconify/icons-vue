<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f7mp4able"/><path class="j0ugzx43d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mijn-aegon" /></template>
<style>
.f7mp4able {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.992 22.705h-9.024m-2.235 6.747L34.48 9.083l6.748 20.369");
}

.j0ugzx43d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 14.707L33.294 5.5l9.207 27.794l-27.794 9.207z");
}

</style>
