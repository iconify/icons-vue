<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o1ecvcwgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:safewa" /></template>
<style>
.o1ecvcwgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 42.5h2c2.216 0 4-1.784 4-4v-2m-37 0v2c0 2.216 1.784 4 4 4h2m31-31v-2c0-2.216-1.784-4-4-4h-2m-25 0h-2c-2.216 0-4 1.784-4 4v2m29.426 22.191V11.69L30.764 7.5l-7.284 9.428l-10.406 4.19l1.04 7.334l2.602 6.81l-1.561 3.666l6.243 1.572l.446-1.048z");
}

</style>
