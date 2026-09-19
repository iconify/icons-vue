<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fv3bazyzx"/><path class="g_99gda8z"/><path class="c654awb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:supercasts" /></template>
<style>
.c654awb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.218 20.686a18.226 18.226 0 0 1 25.656 0");
}

.fv3bazyzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.442 11.148l-4.387 4.407a1.917 1.917 0 0 0 .001 2.7l18.6 18.598a1.9 1.9 0 0 0 2.683.005l.006-.005l18.599-18.599a1.917 1.917 0 0 0 .001-2.7l-4.387-4.406a1.9 1.9 0 0 0-1.345-.56H9.791a1.9 1.9 0 0 0-1.345.56Z");
}

.g_99gda8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.894 27.363a8.595 8.595 0 0 1 12.113 0m-15.451-3.338a13.4 13.4 0 0 1 18.885 0");
}

</style>
